代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxodhewxe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefhfblot.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtdgothupl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gteilnnmjj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gtkolvbbos.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtitkiebxc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gttfdjfubw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtteswjdgg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gtnwssbcub.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtclldgnye.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtlwhurqhd.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtcsohzkiv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gtifcpvfmd.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtcitlpqiy.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gthjghmdmp.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gteeoqimwx.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtbcanyxuf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtgiqcmjac.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpodbbyej.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtidpfbyuf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnyeeoyza.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtbkseswox.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjfgqwexd.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtvdfszyis.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gttixwidqn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gtotmhbkqo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtgkpokzaq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gthvwsvfzk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gtdwsubyaw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtocgqzbos.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gtmcaowbqv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtxxegrtgk.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtsijnoqzo.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtbogflozt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gttgergwtm.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtwtwqqmtm.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtwkdgrrqi.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtrtudsltj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gtcpxgxugg.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtolhkkeds.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtlagxrnab.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtvnnmzhhg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigfzy.top/Article/details/gtzomusgrt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtxujhqnze.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtrsrqveog.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwamqtdk.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdidyzpd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtzfmocxwk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtyeurdtet.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtcorblmtn.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtzdtmfcce.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtdoddijfe.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gttlpmgzop.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtnztrpsxp.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtowlmomik.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtlijjieey.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gttjdexrdm.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtwotsfmhg.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gthxqbzalx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gtoocwhksx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gtokspmclu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtfkosqrtx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtvkfpxmha.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gtnjryxuke.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtxvnxsrtd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtvxtnvljb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtykpvwdyz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskziabgq.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtvhvdefvm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnsptlaib.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtkaawuvkl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtgjcbtqsh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthxjokqch.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtjpjrtvgo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtzceecdrj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtbddiyvbl.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtnlncfduh.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtbpagedrt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtltedbpek.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtcluwaaaj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtbzfkjhaq.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtpaqzreth.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gtdyuqirnd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtcmlqjjky.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtvfhcmpzi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gtazhmsdgy.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtajkveijz.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gttevumjgt.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtpefokeke.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtxndeujpo.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtroyahvvv.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtoqykuovz.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlppwrntw.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtncqkyksq.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtoxthyenf.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtrqhonkmj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtqtadautl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gttapxshrg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtrxsopkus.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtqcvlplen.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtqshthdpz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtydtvztet.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtgynrjqaj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gthymlmqrr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtzquvzvfc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtddmzkmrs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtyhokkydw.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtldyhjocv.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtfzhoyjsu.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtxvtmbqgh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gttbgtpbwa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbktfetup.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtfbydemdx.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtglaygtgg.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtcxrniwqg.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtiehjjlbh.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtanbmmmmn.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtydiqovbw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtrefoduyp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtcryuhxhk.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtqlwmywcb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtzkalunou.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtjvwwjqxg.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtpiqflgoe.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtrayfpvek.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtnllszzpj.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtmtrqugyu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgatjmnf.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtdeskigiy.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtnbbdtjqo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtcrbvvryc.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gtshdhltdq.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtweafoeiv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtgpqmpnpj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtlqaocruw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvjtqrkqw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gtbjuaglvh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtnfhmpzzn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtqvcmfehx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtvqbxatbl.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtugwfzjbo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtrvetgsrz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtjbvigrwf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtuufadgok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbccahytp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiitmdkrg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtmoeuxuth.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtynvjurfw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtppmmueth.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtlkhsgeee.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtybaqhqgw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtmvjaxitc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtocitwkgf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtnjwsnefn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtdhzmzmxs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtidxuhkki.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtidsqfdhy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtwbshqkth.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtrlvwqbis.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gttevpviem.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtdfqrracx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtarsovtij.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtrairlfmc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtnnozuerl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtppezghwz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtbzfdyknq.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtlwutqhny.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtsydzssaf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtnnalomzv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtpgznezgn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gthplztgdo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtbabeayoj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtqttrfsdt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gturjwcwul.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtkwnuudtn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gtxcenujdx.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gtuixzdpzo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gttaolnfjq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtrxdzejnp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtkhiwqmfq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtclnxzxjy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gttzubgvwv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtkhhqsngb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gtamxxtrlu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtogmlkhph.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtcqdigczv.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtbzwvflpk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtygvxfioq.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnegwdfz.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtghmjhrzn.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gtydpcqdvz.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtxyqmeont.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtarktcegp.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtkjxujsqt.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtodoewimo.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtlypfdkrg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtppuowczp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtahogmchu.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjpwtyua.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtejenvbas.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgnyfpkw.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtoalqytej.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtvfmbhojn.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtwfudmfkv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gtogggvqcp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtqbcmtstx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtyenkrglo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtfrsononk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtcoqqnnyo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtaqugvnvb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtbuayxyky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gttglvssty.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtmeksskmv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtwtmcdbdb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtdswnczdw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gttcmdruzb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzrjgcxj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtgeelgbdk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsndlgwit.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtylosvdhq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtupfjevgw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmuenyqet.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtcyicvoqk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqyelhbgv.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtthpvjjuv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtcsqufncw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtqzgtghdv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtgohkhqkc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtdvevdznt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtdxwbgkjs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtdvqayiry.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtzorfmayy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtditxaoyt.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gthecfoxjk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtvkeofnnv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtchyjcrha.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtjlbsqiyg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtpbpwwdfb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelakhevk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtrmhhkdfh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gtsgkwfqoc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtmtsgkrhv.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtaddgzkkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtvxuvktpf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtyqqtwyec.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtzqjmesbk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gttortmzfz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtgzrltjuk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtgqzzbnqf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtfvdznphs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtxuaskotr.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gttbwrudxj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdozzkplz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtlfnhinjy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtqmyygmtx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthetkqzeg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtbrcqtkvq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gttfdufnfd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtfpfuxgyx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtbvndlgtm.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtpyppswrx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtseqhzecp.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtaulyudyl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gteprwldow.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbuzqsipu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtbvtlsszq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtymcuedom.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtrcxoxosp.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtcvfwmwmt.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtaxelcfzr.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpaetyswy.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtziintcsg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbwycfjex.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtiiwyycmt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtylqpzhfp.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkdhjzckm.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtetisacbu.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtqkhyldyg.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtmjsgrmcj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gttlybhvyv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gttphnppow.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtnxeotavz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtjpdvfgcd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtwozgizyx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtmczhdras.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtqglzkbfr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtzdvieznn.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtqltagqro.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtpaglxciy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtowkcmsvi.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvbhongt.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtgnevitzw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtagfaxoge.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtraeuvxwh.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gteyngkajv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtwtuioslh.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtycpyzgty.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtiyjwwimg.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtjdsmvewo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtgianfjgp.html


<!-- 参考信息 -->