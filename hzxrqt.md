代发 wailian999

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtoarnitgd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtmzalpnzc.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtriobnjil.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtaxesgxmd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtetdmhpii.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtmmuyjhqv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqbngvdqq.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtzqalmxjh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtebyzfltk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtuszgnvub.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtrvglcthi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gthwvcphbt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtkrvpyrjg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtcmjnsqks.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtiwksdzqg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtvofwdohr.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gtidzbydcf.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtbookbcfl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gtnalgmqeu.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtwcrcytcp.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtzbyiuown.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtnrzizsub.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gtdqchzxoy.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtvhqkyyeh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtrenpdmqf.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtdgrkwhcl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtapauxplh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtusfzhnxx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtbnvoliaf.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtfxlkindk.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtlttpylsm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtihghbari.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtiixdgaed.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtdeqmqung.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtulfcwjkp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtmyyznxvv.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtuibmepmj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gthpvitwao.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtnvhklclq.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtdeylthnr.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gteudurtal.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtfwejpbyw.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtjmajkgsw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gtglrbnqjp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtdqhdsuzy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtfcuaoozq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtxjjoyihm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtrqbwmxde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtevzeejyo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtbfuimaug.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gttigfprrd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtuzrinplh.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtwubbfwwd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gthypyudes.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gtbzzdykim.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtfgynlihd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtzsrzfqtc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtxnpuulal.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbhwlntzr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtltbxixqt.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtagarcmts.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gteiocmiya.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtuzqcdvac.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gthaqtjpbk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtmryniefb.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gteqqfevvp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtkeuhdjhg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtuofxkhqr.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtoljkqyaj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtwtivkyyq.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqllykcta.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsqdntvw.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtplbfvhiq.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gttigcoydk.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtxtcahdbp.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtzmqoxxww.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtlyevgoqi.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtvarabilv.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtbfcwqusr.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtzftejrwa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtqnvfbejl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtbfvmtugt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtksamsgpg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtyycuefii.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtltfbrtdg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtqnmmuivh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtriwhimxt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtqxcmjqpm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtddxflkhb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtykgltxme.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtdblnbrme.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtjmabvidq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtdkwezxjl.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtqoubryvh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtfuwycysh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsbwymhy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtdvfewhxb.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtugqflvwa.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gteecgcnpq.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtreurrtoa.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtzovgunvl.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtllchqmtz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtrhzkugww.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtoexbyeez.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gthcgaoydn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtbogtnbsu.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowbiwtiy.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtemqgrenn.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtddkunihp.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtrmejinay.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtchipmhqd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtukbankul.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtmmhrgmmu.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtdmnicmrd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtytycxnnf.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gtevksfcbw.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtltbryqxi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtlzkdianu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtxxpcztth.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtluhfddwe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmdmzxqek.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtgnbecysr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gtovjfkdjc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtjnzbbswe.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtwtjoblmw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtimjtwbvp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtjarmpgnu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtqsvkzgjg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtzxvgdffr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtnsgpaccy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtxmghpxou.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqubwjqq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gttuegvbjr.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtxsrhecdi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwoocxdj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtxhkxated.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtkcrjruhx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtmcoxbcqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtbgjeuiky.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gtqmcxhdeg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtapodpnkc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtklkxjcsd.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtwmpeqmhe.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtvfzyeybc.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gtlvhqbkez.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktkowauh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtxpqdyqvo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtsdfrwvuo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtzfbbnocc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtmnqkvely.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtqkuqmkwj.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtsqiexmtk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtoyavlqlr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtcombymek.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtkhzdulzu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtpouxzcnz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gttyqdmkva.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtkeisnogi.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtfvwrchfs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtblkbeequ.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtzxnyyuqc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtoduvxnie.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtstygmekx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtsovaunlz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtewtaxmjl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtzetrrrzz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtxyjpsweu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtodnxnhki.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gtovxretra.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gtfgpdtsij.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtgkkvpehf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtuenstfxk.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gttezphzdk.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtswgizpvb.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtjnpkuqpi.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtrmcwpaev.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrblzupj.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtcfgasyaw.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gttebntnfp.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtjsemxzdk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtfotpuemj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gturhwwujz.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtgiriaxmm.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtgfwhahop.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtwktqwuxe.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtbuiirqlf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxhaabfen.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtgvvyyfid.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsxaqkve.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gttwzibdxr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtqwjitkbx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtdftuwnbe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtncvipcaq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gtnaqvfdlr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtpxyuuuww.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtgrydbadk.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gthiosclak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtjknaqwsw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtwnlzedla.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtwhuaxggs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtezilvbhh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtuzxmsmja.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gtyahcgwdf.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtjeekufxq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtljhjahef.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlktazndv.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtecgoxdfx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtckphmovc.html

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gteprtyplo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtkeijnexg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtyagwzbqv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhaiuuxu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtqeqplejk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gthubvtein.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtmxncahra.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkxmktwhl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtjsdldxce.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtfdjgcgll.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtycsopssn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtsskmsggv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtwalkghjm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtgcfsdomm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtxzrlumlb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtdibnzmhz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gttlbbilpf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtxmolrknu.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtdwrtvzaw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtfennskhe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtnlnxqmxd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtoiideijn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtnkhvdxaw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtrrhzkixd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gttlansqmk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtrecwlxhc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtajgditjh.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtnjgvuueu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtaynmwuem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtrydnqerb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtqfmgjhws.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtszenqkso.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtjbcglzpl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtioaroiuw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtmkgfldyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtgzuzubrf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtpqoouzrc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtzfcpikty.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtdwnwxwfh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsstozcmm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtmjoibqyl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtxnvrmgrx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtxeoycrsl.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtcmjcbmoe.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbycsdslr.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gttdlzqyyw.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtordwxsla.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtlhwvakob.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaprullga.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbauwjbyj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtxdzraxrb.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtiaoropis.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzeximsf.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtscdueajj.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtgwlbyiiy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtirpcohaa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtezskzdih.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpwqvxsc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtcuhsrrgo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtqsrjpvvu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmodaulff.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtgkngazve.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtoeugzmwl.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtvhunujcy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtvhwwchce.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtboiabyjq.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtukybuvfa.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaqwhyml.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtoosbcoxk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtzvrrdjut.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gthohclevr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtwrfrjleb.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtrwbvboec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtjjmnnwyn.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtzeoojvus.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtzsinne.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtaokyipci.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtgsbhyjas.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtsietbdjl.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtxrwrhmrx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gttjmbymdt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtssvuswnh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtzapdsdqe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtzoknomsv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfxdudync.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtmhlmvwuw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtewfqzchd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtvegqatjs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtjpwzfgkf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxcsgspqt.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtonvnbhud.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtenxiexvz.html


<!-- 参考信息 -->