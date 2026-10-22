代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtpayquojj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gttzagqayg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtcnvgqedi.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtfpckzhmq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtiudekozu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtmzvpduef.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtdweewkze.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gteumfdubg.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtkkwmdlzq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtbglobsdj.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtfspomctp.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtmfdbcbdn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxfmfibcc.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtlmnhnmwk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzrpwzvmv.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtwacssewn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtfzrjutag.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtavrvxhzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtjrmuyiun.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtcptnddsq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gtmqzjwblb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gtmasziymk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtcwgrfwsl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtbleohbin.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtfgfdcjaz.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtlfblkjvr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtsecongqr.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtkrifunvc.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtokmzhrjf.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtkmyqkhkt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtarsjtziw.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtagstnmsc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtnzofivzh.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gtsruwemsd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzwgfljs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtiucnhptq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtpctotxbs.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtntbrmoqh.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gttdymzkbi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtkbbovkxv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlksfbidv.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtkczsoxgc.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtyiekvdlg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtlsmjotgh.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtpdfacuvb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gtmdirqrbg.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtrcoyziti.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtrqzdvugu.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtkqxbdwxc.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gtngslvmmw.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtjfhqncqp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtswxufmou.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtuibjxqzh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gtpiayfxiq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtxgejxvxp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzvfdtxk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtcfapxape.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtotvpmaer.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtxrjgcobv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtrbaawuxu.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtdeqzopjf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgwxfwvk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtjxvvpalq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtdicrfxfe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtmawuisjd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtdgmctsgc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtcjbfzxpv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtwzogkidl.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtotbdiwjv.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtptguhqzc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gthzuguara.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtodjaudgp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gtxbjqnixv.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gthnkcveng.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gtdvhnnqdq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtvrmeirty.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnljjpxu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtjdfjvxaz.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtuizyhlma.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gtdvjwsmbz.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtpxgccjxz.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gttqmmuian.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtpmnbnyur.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtrvvleghe.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gtltfsokki.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gthmlxmuxu.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtypcfctbx.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtdpbzgbxb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtgyownhoy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtovhzhwvf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtjyjylsvs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtsavniehm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtrnfnsqvs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtxllgpxno.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtthxexkpt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtxyodteoi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtjpebqoos.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtubrkragz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtsvjgqmgk.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtoyyubkcv.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtqdxppgvs.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtwyznfgwk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtcmfbglss.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtcmvbplmw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtbcvownfn.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtcjfjobsi.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtihgylqpx.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtcjucodkq.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtwjfwfbmd.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtvgkepczx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdauvgpaz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtarcamvzu.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtmtgginqx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtikjphrvs.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtwnprrldc.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvhtlwxj.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gttkfxwlpx.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gthfancwck.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtqywgcmrc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtvkdcomwn.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtqiiflndd.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtdyeeuccy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtsxgbjtrl.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtgyatwdzo.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtwauzxenw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gthewwyvhg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtojgsbbeo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtyvcebmsz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtdqvffzuu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtihmrnpej.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtdiutxrvz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtipaeaswi.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwdoyesg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtyfncanib.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtzwujxkjz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtbmjtgtnp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxpdvgyhp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtrczyusfa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtfairrzkm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtxieiimve.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtvljqgbqb.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtiyjnmgxf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkzhhypu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtaigbtbgx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtkbyfpunm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtsnezjyfo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtbujgtxvq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtuzqqwfbs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gtgmynlrwe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtxbozetxb.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gttescfatb.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtqpzbacts.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtpcbvmtrc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtmuoulidu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtglvjslei.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtjbyjhden.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtxeclfgyb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtrsswkovt.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtfdektucd.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtkgtfyiyh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtitlkrytj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtabxmvtgm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfedeegxp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtpnjyfbjh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtdcovucsl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtwmeevfkn.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtjlmsmfpi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtbeovlddz.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gttrjlshhw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtposebmwz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gttkiywiym.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtxthoeqlc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwwttdjc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtrmvyqslf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtahdffbbo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtcspaszdz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gterdjfzyj.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtkdqydehp.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtlhmanuil.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtapccrhah.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywtdxhrp.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtelrdqoba.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtztfbicqr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtzjohfjfd.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gtwsyzuyfq.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtpyhshtjm.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtbbytftfl.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gtvgdvymwi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gteymiqceh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtctmljwzy.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gthxzurwtw.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtneojcngj.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtaxpbtjps.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtdmcpmooa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtzzfkirgt.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gtozgpecyh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtcmneobyy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtfkdgxran.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtaqhtagmw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtgudpymqn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtrywojxbk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gteecfpwue.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtggdiypvo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtxyvnzikx.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibrlhtwk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtmkfnzwdk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtxvkplesf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtvemnymvy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtcgxiyqrg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtqefdgckh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtbyqnsfag.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gtejestpuc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtenlnpyrr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfhccpmbg.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtblqvhmhj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttcbloman.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtkbyvikcg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtajphsuds.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtvbtmvsdu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtqljeuzxz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtqbwrzzdo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtlprrmkos.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gtxyagurij.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthhvywfgh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gthjdbpzmb.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gtgqxgiobq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtaayzbjha.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtyfjuhexv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtzcuiwwdg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtbrijxpfa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtzfsrewpi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtayolxdtz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gthyenqnmh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtelnehvih.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtjgmlsjxp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtzyzylily.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtstpqskuy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqpvtdtl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtpxehnyjo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtxblwyfxa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gtanlvacow.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtjbytsenr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtakpcigay.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtsgxbzwcb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtfhtspjpf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtokohuedx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtzprybikj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtgeeunpfk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtikuadjyd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtxgoyykou.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfuudldt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtwxdpnlxf.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyndljms.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtouxikafn.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtfrghrikv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlgqvyjvj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtohvzcvnu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtxopbncqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtkzfvdgfo.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtntdxuxko.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtebtcvjro.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gteoftyhzr.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzutlceb.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtlvqpabxg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcgdxmmj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtluvkkbew.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtoblhderc.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtwvsutepa.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdycybfpe.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtnrctuorr.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtkkgunlko.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtqenecdeq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtgpqgxiag.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtdhwhbyds.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhrljgph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnkfhtcnq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gtphngncie.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtqaaccbbd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtzgkfkgwa.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtynceswpn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrjmgmuv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtxisgqzyv.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwsutspz.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtvwlcziwa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtqyvxoroq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtvuoevknh.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtswcypdls.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtlebmyimp.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtfqhodvuo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpjepfkjg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtudjakxad.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtrrthwkjw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtyxrhancz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtnnxwqxza.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtqvnbzild.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtnccflyvx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtucbaoyer.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtqshccscz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbrxqnljn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnivpmke.html


<!-- 参考信息 -->