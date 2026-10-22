代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gt2vfaxersk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gt2mjltqppn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2gvsfbkcv.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gt2yervduys.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2oauptbuw.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2vjacirbl.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2zhaabdvr.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2vxnyhxmv.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gt2qlxhbzfu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2eljrcqlt.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2rbhczjqo.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2bizbkgtm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xwspppno.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gt2gqhkkiyf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mzdwzjmn.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2cviihjzq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gt2rixvlbdc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsalmtgg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2ocbtkndu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2gtonqucz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gt2xhiwvsvl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2zdwwhftv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gt2ibmtlpbf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2cbxxlsiz.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gt2ltfbidtd.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2gjlhtuuh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gt2amqtsrnm.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2hhxmkkgj.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2yrexzadq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmegqtn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2mkbrbwcp.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2dexsuzyq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbwrdrsd.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2wlyxhjaf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gt2dneyeeac.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2fxdljhgd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2dbcclgfh.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gt2almffdtc.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2wbgotzem.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccqphtab.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gt2mfsvelan.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2jgjwpyxd.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gt2sqadlzgd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhzjefof.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gt2isuvdrdf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gt2frhkmtnr.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2ayqdoygj.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2zigmhunm.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tymmykaz.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2kdbiwcsr.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2onzeqwsa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hshmsfgu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgxjispv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gt2btxxozaw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqxynsep.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2yevtqtzc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2qqqjpkvz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gt2zyclhqrh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gt2lnftidmm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kurafyqe.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gt2pyhpgvum.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2bxkmkuyw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgbmwtml.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2wtjqdpql.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2gmvkfrja.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2enfmvhml.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2kujbonow.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2vfxalnzf.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2pjrrthui.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xejjdwpl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gt2egmsosdf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2wyvarvyq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2riexfqau.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gt2rzflhmba.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gt2qwgcdkur.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gt2cxocgcav.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gt2gkewrkon.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gt2sjkccekz.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gt2gsndvmph.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gt2vvagnpvc.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gt2fsqefeyc.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfpohodu.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2pufepmkr.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2phmjfsge.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjxlbplg.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2tjaousow.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2kqewcggn.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbdisqga.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gt2avodmvbv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2vdwqrisp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2wqvgabrs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2fylgicau.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2isbkakiy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gt2ynuiztii.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2otthibzs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gt2yhmiseqm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gt2kafdbzzn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2vnsoqazx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gt2gohmakbb.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmedmliw.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2cbivpkyx.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pihdpqus.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2qotpsfzo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2woervryg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gt2ukejgink.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2bjflmqha.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2bmzsigxh.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2nvrnftki.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2eqhzpian.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2zeamelrd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtcehvti.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gt2zqnqwdbu.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwqrhthz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2upntfkmp.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2kpderids.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2rqyyaszi.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gt2osksazaf.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2iwrgovxs.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2knraymxn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2cegahgjj.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2fckcfgto.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2wzzvmjyp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2upvgbzji.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhnoxrdb.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2qlsbrxmx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bybdaxyy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2bvehxtdz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxejggku.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2hfurioxs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gt2rcysxzes.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2mbhssfvz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2srpghyrd.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lheujrgg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gt2iiqytdys.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggcbfwag.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gt2skjzmwui.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gt2yaybhwoj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2lgbbbjyc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gt2hqwaovic.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2otjeuily.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2sinuqaly.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2xpxhhnya.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gt2cmrcflif.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gt2rmrjylxr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gt2xjaalnfc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gt2qsznkbzi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkftnyca.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gt2cedyteaz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2lfcarjjq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gt2mppozxln.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gt2kgfkgcdj.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gt2xsopfvzh.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gt2qwinqofq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2vqvlknse.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlbqrebq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cuirgdip.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gt2xoiifzpg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gt2tgruwbuj.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gt2ljxecmkh.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2bgueggtn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2hmgxpgdj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2yooqzkol.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2kxkageih.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2gtbjsuas.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2blwyljgi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2uhltioyf.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gt2jsjujats.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbviosgm.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gt2kwubpgdm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gt2vjdaqrvh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gt2eqpmuqxk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2cvmddrwb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ledcqjkj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2ejeyexsp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2iihpftho.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gt2kvivshkz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gt2vasjbeii.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyjyutqe.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gt2nkcjyfcq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2phovaosj.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2yyjrmkza.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2watxcfoj.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2hfsuqisk.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gt2hvqfcpdl.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssfhyoxh.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbbiitre.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gt2jbdlgqrj.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gt2ghcnfwii.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2yxyzyvuf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mltikqwp.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbtautcc.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2fzfayljt.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gt2onmxnaeg.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gt2lkfahnhy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ozubslwz.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2vtreswny.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gt2glhauspl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2wtksnwic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2oeyidykv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2kmxcikdp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elwtanlf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gt2dahlwany.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2xduuncnk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2crjgqppx.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gt2sqyimyyz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2ikxtlbyc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2tlskdoaj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2ueemasro.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2nzgzsccm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2brhwusio.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gt2iipwnyya.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gt2efenxgtr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2zvgnygny.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2tlgolhty.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2zwalxomb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2wtklorwm.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gt2dfmcwwjw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gt2pztsiuqw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2rtslskow.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gt2gzldnxti.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2pogfvdkm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2eaeklris.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2lslbrbvj.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2emcponlb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2aggftbmu.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gt2lmmfibem.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2griqtfwj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfjkzqco.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2lwnxywtm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2szovoooj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2vodzzlbl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gt2biwxgnov.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gt2cfxafugi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gt2pvfpejgv.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gt2bluncvwm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2jbsbyand.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2bpkxswlm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2iyvtexbd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2hnqrqwen.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2ywepispa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gt2xpitpdkk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkpvcbih.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2zrnvvjwy.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gt2vrawyegz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2wgcjywxb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2foceovpt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2bsqruiyd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hluexcpw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2nbhejzme.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2xsxudfdc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2yhpamstp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2lrxxromt.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2kssqcinm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2unkiflpq.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2thocwgrq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2plaztwzm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2rizmeifs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2ysbndpkq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gt2bzwychws.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2gektsuhu.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2apxlgisf.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gt2zaluzdyo.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuyurqow.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2ifafoiyw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtjpmzff.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2hngubhvn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2doguqqqb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qbanooow.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2txlkgrhw.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2logfipey.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gt2whcjvkkj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gt2fizxtzuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2brqfqocs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2ybwclsyi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxshvheo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmcxtesd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gt2hasmxjsp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2kdrtcxcl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gt2nbegbwxm.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2uawfnlvb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gt2pajzzixq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nfmngarh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaoveeb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2hpexngqo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2qamgburv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gt2sjyivagf.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2udpshiuh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gt2hjfzyhyk.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gt2tprbosul.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2dkjcpexu.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2nqjpnrsl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2gscyuqof.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2xztrcrbu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2jcohduej.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gt2dfrejfwi.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2lrdusdtp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gt2maywqxyn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gt2szovvenq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2fofganew.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdvymkxy.html


<!-- 参考信息 -->