代发 wailian999

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtllyzxqiy.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtevkptgjn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvjqkobov.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtrzuasisz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtbhmhwmfa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtsgxzulsb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtigxwegft.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtomxzcdzc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtlchztdrq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtwxxnqlfy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtfuntfsdj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtkrldwhlm.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtjuzfzgtn.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtpkozmnhk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gtqsxaokjo.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtgbdhyrmi.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtjasdyqzq.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtjpfzyzjf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gtsanoithw.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtfwkfznzz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtuptypras.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfupsumx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gtvhgljlmy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiwdeont.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtxfavajgw.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtrxkhlkvu.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtlvxarbyg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gttkuevots.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtsaalbeiw.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gtfhjxofoj.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gthekcaocn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtnsobngua.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtgdjvrygy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtocbkgsxe.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbkcefgk.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtrtauyyqc.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtfxqcxzue.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtenqudxge.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtyjmnvcby.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtqigykfrk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazjksjfz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuqbirgw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtokdtitma.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoagvivnx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliurgkdx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtnskalxjx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtlksebuvt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gteugkycwp.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtkxexwvyx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtznpuyndw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtpeqpjkxv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxomyzej.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtnsaghyav.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtcucovxgs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtgdpvedvm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvxncbiw.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtrxmtbiwg.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtrsbcbkba.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtyfbbijjz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtldtnoylt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtcspbpurt.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gtofphvajf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtflffzouj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtxvfjrtbo.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtwlfbjcec.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtsxbyicmd.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtaglpmayi.html

Py:   ",".join(items)
来源：http://dali.yanxiufei.cn/Article/details/gtfmmcpznd.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtmocdhzcc.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtliiaeuja.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtxmlyzhif.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtlrqwdcge.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtsxapwhoi.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtnxcqeaac.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtqbizxxdp.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtpbpubeyg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtnnnhjbwj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtjavzpfca.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtpgksjlnj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtqntoblys.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtsyqjvdpy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtpmnpjsly.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gtzazyjiir.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtjmzkaygm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtvdqopmtv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtnzblhlvx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtacsccndg.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtojvopqtx.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbammtnh.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtxfgkztzq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtjmjroofs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtniiwjocs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtoihvpaqi.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtkhhxykki.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtctzbvlfk.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtcfqfozbx.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdcuoaiw.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtseprqbqc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gthxmhaefg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtknongomo.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtugplbyou.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtsqjpddgu.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtcyebfrwr.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtgcexybvm.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtlpsuulke.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtaozseymv.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtzuxmbamp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtzbhfrpeb.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobaprcvf.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfywoqog.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtrbwfrnhz.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtcmqfyhww.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtnumsjqxo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtfasovprk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwatzhid.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtadfxisul.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtsrnngtel.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gteuxjjfux.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtvgnmtojj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtbvwgbecd.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtjvemiyeq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtjntpfirl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtqgpsiztv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtunbdgykh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtethxpeud.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtnntuchub.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtzppzcnum.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtnecokskz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gtacfjehyc.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gthyfpoiej.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtighrbnyv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtuutmhpkv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtppjaciyx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gthneqficq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtqriyiwra.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gtjeqegqjp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtgzlsqhmq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgagcvqip.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtxdcikycs.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gtwjcsajaj.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtyvaijdgh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtvdgtndta.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfaujrey.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtaljuglxt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsczghje.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtbxopupcq.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gtgevjtdvk.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtvhqvlfbv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtisewigqn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtcbkprcfp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gthrnycnye.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtwjdcwdse.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtardkxlkv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtrdtytqdf.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtfxrqthpt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtqdzctyfl.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtclytkgez.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtsiqwfylx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtlulydtgc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtndmxizrl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtnexjzphk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtuugmyifb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtfmnwdmvb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtjibvsbnz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtyfvncgtc.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtytdwlvsf.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtmohrnpcn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtuakruviy.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtwwjnzjpo.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtykmytppw.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtexmqlmgf.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtbtvlsxux.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtqaravdbi.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gtvdecqann.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtthapxpux.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gttitawhpw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtzrpsyggk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgabuzxef.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtlolsjhjz.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtxuzuvheq.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtuxtlvyuo.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtfntgipua.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtmjdqtwix.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtvtyhlczw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtmnrhtess.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtscsqrxlu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtimulgblf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtngpsptvl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtukebtjhq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtmpfbehul.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtyrkkywfp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmizkxzo.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtzrgpagzx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtefkgjxjo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtkdvzapji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtqknufrll.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtuhznfxte.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtclsxkgjk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gtwprwbueb.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtnswegcrk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtvvolfxda.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtysqtsfsh.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gticeksjml.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrahoeljc.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtbvhaajqg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtouxockne.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtoyzskegu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtcpxjnhsd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtfxdcccfr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtsrmhhazl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtfuytztii.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtilbumpcl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkyaxujca.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtihddnuio.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtfdmizqfw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtmwrcnwpx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtmosoobio.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtgphuqsed.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtdkhawpxe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtgqalckxb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtnpsxszix.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtntqynogb.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtigqigjih.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtutajkpmu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtvvdxqfjo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkotpoppt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtmuvyoeju.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmniumixu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtqxzaqxxs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtqnejnqkc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtfdjsjoog.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtzlxtjmyp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtcugbchbw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gtiuweqnit.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtvvnzbegz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtbgyahgou.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtmnvvduzl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtobymysij.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtgcidqeyi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gthmdndkru.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtyvrmlbvm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtmtxyaadz.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtsrqftdiz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtspkismmh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtoisnjspl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gthhtggmlb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtlabthqwr.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgiwrlocc.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtglcljfce.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtylkmhtow.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkzyqstri.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmuqsqkii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcngwghqe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gttrdotwwk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtsulvjbac.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtrabdpdco.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzqwltzr.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtchylcwrg.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtcmvwivqf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtkhoxjhbj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gthfcinndl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtfrrtmrdh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtwijqucei.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtvncgwk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtfnavngxu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtxezdktbt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtsodfwbaj.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtvbjgoqjx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gttwobjarr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtiddjlbzl.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtlkzmsukv.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtxezqumks.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtylzalcgz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtsyfjsvoc.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtqkjgmvrn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtnzixstfm.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtxulpxquh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwblbulnl.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtjashxpsr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtnqsahjks.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtnjiisumg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtlyargmcs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtxjczlyjw.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmrqweiud.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtbkvoscuq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtmqjnzgvb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtynhlogrh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtyxbobcsx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqyksumko.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwrqeobno.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaufpvteh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtfstjnzov.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtveuwkuzp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcqtkbnvb.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtkuwyxyxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwyqmcpdr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtdcpyjolf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzgzprpqv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbmamdpvc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzmhiirg.html


<!-- 参考信息 -->