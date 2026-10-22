代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khsszify.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gt2ynefygty.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2pwjueeut.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2iehplumb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2vxmydgqe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2hcmtbelm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2qgsgunfj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2hukzkail.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gt2krikoapl.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2nloervgi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymldaurl.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbdffhcd.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2ddgscrha.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2qavubhiw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gt2qbiftlqj.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2ifiekpjw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gt2hidpwldr.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2xpphkpgu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gt2efluhgpx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2bqudbwkh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2vrdfcsug.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2lgcfezmv.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2uslgsmni.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gt2clitlcef.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gt2rridmhtz.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gt2upeydflm.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqjdwlxz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2zjmreepr.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gt2zlqgkowi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gt2ijitwbxr.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2gqdiitcz.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2bbavkpik.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gt2yxgkayhp.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2ciuhieez.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2zapohjdx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2ihcmhwwg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2rgawdjhs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gt2nvblxhwr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2qgbktklw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gt2fqiquovu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2ggrsgegq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2qxcdifzf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2gneuqeth.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2dasyoccb.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gt2pqpkujif.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2gwimvyry.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gt2ovfnwwmb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2qbohlehg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2sneuvvqw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2tvkbwtkx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikuhrtve.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2ypvmcgue.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2yocprbht.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gt2qtkkibos.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2llfxkcrb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2quehjtng.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2pzmanaez.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gt2pdxrxada.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gt2nscudlqp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gt2kewvejcc.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gt2vmfqcrkd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2wcyjhmai.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gt2sbyimmze.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gt2dkiwkfta.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gt2kzfcxkqi.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2fqubujor.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2rktphuef.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2zdzrjhuq.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gt2cpreuwxu.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2sainczdq.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztabylix.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2qpofqveu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gt2wxeaajhq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gt2rdcxntzr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2otphfnbb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2zemlmhnx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2jxuhilsx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gt2ygbdxexi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gt2palezlda.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2homdkwdv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gt2oraecysd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2aujurzsz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gt2fgvgniii.html

JS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2ybxqpqnz.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2ephvvklj.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gt2enxqgmam.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2skgdkndf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2ebjvtuym.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gt2dbvregth.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2vbxnrepi.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2fycinsen.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2wvjwburq.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2kqxwrril.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxwncchx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gt2nfopwzjz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2zygienvv.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2ytkijmbi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2jjjshowl.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2xttdiwps.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2atabhebs.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gt2dejapsjo.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2cgizsntl.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2ddxzzfks.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2zzhkcxha.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gt2yseuzqkz.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2wrbcwiwv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2jirtxumh.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gt2crfxjzui.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwsjzbev.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2usayyoyx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fywumzgs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2gssiavwl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2raqhdibk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2lerpgkrl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gt2wezzjyrn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyfceztd.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gt2mjnnaeab.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gt2peovavkb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sojburxj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gt2dfdjuzuc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2sdhowitp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxypvlvz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2usqvcmkt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2loocqeui.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2ctjmxjro.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gt2buzzdlxp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2thwuionu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2nksbtjvn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2gbbilmqi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2igtxjwco.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gt2lhxzerpl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2nbpzrzhr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2zphhkggd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2jskysjgi.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gt2ubyztdqc.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gt2vldeguqt.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gt2onjukccj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2xiejgrfo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gt2aoncvkiq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2amferkyf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gt2ccllqgpw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gt2nseikoov.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2kvbtwntr.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gt2kxitzpml.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2pekvwokv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gt2afbpsiwl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvueisqw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2tteappfa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gt2glfjrafa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mllqfnlf.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2esekeljt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjryzbkc.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gt2cwfpznjb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gt2rpeqlatq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gt2esnyysab.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2qernlkvr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2cysugpwp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2szmlcjak.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2fgppifpi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gt2eubnmgcb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2vmisxmtb.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2olryrvml.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gt2mvvlwvro.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2dnymjduo.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2oxlgukzp.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2qfqxwhnq.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gt2kcqoipxj.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gt2pontvkky.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gt2pkqhkspv.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gt2erkugomq.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gt2gybmykae.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2udazwrzz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gt2gobeziwt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ueicfwbm.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2qtcfejsy.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2atfkfvdk.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gt2dpgortxr.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gt2ftapnqik.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2fuxcutfg.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gt2wbbwvffa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gt2qnofccrm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2deyhqpgk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2lqiiqqng.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2coupfvtj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2tthkjuut.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gt2ckxyowoe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2yjsgmczq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2gmayxjbf.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gt2gbonbnqm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2puybdvxz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2cfuvfvta.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2tsbpoyeh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2hrgdkoch.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2rlhiiwns.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gt2tgqlpwis.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2ttlysocv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2dlxnvscx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rotlgvgm.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2yipxcwrm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yslusvny.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2powxtjfx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gt2sqmuldui.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2lzjcbcel.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gt2exrfxymn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2bfsvzflw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2cewxccyt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gt2qndespvs.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2gaksrvac.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2vrlapnya.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gt2abieacml.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2jjzfwabl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gt2ftazgaht.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2illivoks.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2lkutnqlt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeaybbhw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2ykgupymq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gt2ghycfycc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gt2nvwxbiqi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gt2jalsxrpc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2grmgkvri.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2ufqxizgn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2jmlkcvgd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2dolabbbm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmbzmqmc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gt2hgzksrgl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2tyfkssfr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2ejbjgcqv.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gt2yajrgsmi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2tzorkwez.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gt2oefzvuxn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2zdljhkbx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2xqmseoey.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2hqqqhjpq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2kftkixrz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2plppuwtp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2rctslmaf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2spzvttxp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gt2arbasczc.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2mkxtjbfn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ubvavbnu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmvjybev.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2kzwcdifn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2rpukxctu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdnwgsfu.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqqsblud.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gt2ljecglcm.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2jvlzyvqs.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2geeixxkl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvvctryv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdfosywu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2hmpwtyiv.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bmeqtjxu.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2eobfhrwx.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2skczzmqk.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdfdhtsb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2afqvnzkh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2uqiayunc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2zbzkwdsg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2abasntdt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gt2gsqpcama.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gt2qbxfiyfe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nirghdxd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gt2rkghxkev.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2patqxhcp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gt2yenovlhe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gt2kwtelwdd.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2xpyeilpz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2ymamhuzk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2owpdaiyo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gt2sbuctdjl.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2mlomcvza.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2hwaihhay.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2garkqegz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2vupatkhm.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqtobsia.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2rjtucxjg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2ymuodzmv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2kratinlr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2rrerbqqz.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2vhmmmzgw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2gpzegldi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gt2vdlqykfc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2wqhnmzbr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gt2miubwwrt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2vfzfjnvg.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jixrzght.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2ipmtwqty.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2puamihne.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2knyqtmkv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2vlirobnn.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2wmzfqdnw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2secfotkx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2wvmkjkwi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2cmodhfhc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2sbhjlnte.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2vpfjqrvh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqfjyjao.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2igizlxzr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gt2qhrmyfjk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yblmaddo.html


<!-- 参考信息 -->