代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtiwjjssjj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gtpbzgzqez.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtwxiukomv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtulgxugws.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gteclwtncs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtftptcaqn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtbhuyfazk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtvvsxgyni.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtlzytrkvj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtclshplxj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtpoaygecg.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtghjbxsoi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtvzsevhtw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtsoygxddh.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtspjtztwx.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtbbjmgfix.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdctdbak.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gtrfwgdhkk.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtvgowaycd.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtkezacvhe.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjsueyfwm.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtfbymecvl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiwjlueao.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gtowvgzzae.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gtrcnpvvqm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtrzjdmpbe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtrezdetrx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gttgcuofbq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtvctsxufz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gttrtcckmy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtproqahjc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtegesbsxf.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gteubnqeau.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtrxlrrkra.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtuqttfxss.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtkqpchqvo.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtgajdslrt.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtftmcclbn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtschtmgvs.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtbzawgfwg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtbsieyrjk.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtlduxbjbr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gtyeoyiphr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtjddfqjlf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtwfmzzkov.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtmqagvuor.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gttwvgejvq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtdpdeelmw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtngsgfmqw.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtejjpaswh.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gtnfmspmpc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtvxawqbot.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtktumfmti.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtoyewhebd.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtabmvxrgl.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtizodhvks.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtrafqmian.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtezlefysv.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtxhcbavav.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtxtnmpeey.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlauhvpcr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtfgelskbi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtehfqqjzq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtabyiztea.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtzsdupamp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gttculabny.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtxncfbsuj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtokfjlddb.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtaremblzo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtgpuxsegc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gtrzugzdog.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtdhxysvci.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtdsrkbgoy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxaqtwta.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtlxuvrdns.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtbuewcmfh.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtxkqpkwke.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtpccjaxxk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtczarypvz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtuetstasp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtatfuoyyb.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtyphyhccj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtplnhwtib.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gtgljmqaqo.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtsrkbqpup.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtvfbouidz.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtrucceazn.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtgoiorpon.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtzvyqssmi.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtfhfhpufs.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtxqepwfil.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gttpzrcgmp.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtknxcdium.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtocdxewaq.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwjufolq.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtfonyywkh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gtviiaisln.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtwhkasmew.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtrtnecqwa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtzpamvyxk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtazuquhnx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtdjjfkcsd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtkiwzjwvs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtodcjpfqe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtrjrhnbrm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmkxwuek.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gtarnbwigo.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gteacrtsgd.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtjymjkdta.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtfmkmqjfv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtgmhlemck.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtghqrfkps.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtcmvuoffc.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gttybmvzss.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtiwcpqjrt.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtnpwjbmjr.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtnbpzxikz.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gthwfivmeb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtikdfybhx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gteimvdtjf.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtnlebtprb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtnzwytcrf.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gttedzvfjc.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gtqsnfzkzv.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtslzwetzk.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtfcafujev.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtrqjjkzkt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtkvajecwq.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtscxdvmqj.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtrtjqtisy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtkvfapxro.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtzpvoeyku.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtecsxxkft.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtyuyftcka.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtehpzkckb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtympzojhj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtaloyvylp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtpktdmlpy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuysajapp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtdwfgleez.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gtpbleolpd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtcyjekrjm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtpygfdjnm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtrncakftm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtagizjzkt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtiemkmyyh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtmhfmkrnr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxrigkgz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtkemekhaq.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtffvimyej.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtyooqxwnu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtfzyxsjoh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gthywsibph.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtlrwfcouz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtgehfllxq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtpyfcjgjv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gthbeunhdc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gtqhhpctnk.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtlckjmqxv.html

Py:   f"{1234567:,}"
来源：http://dali.fengsongda.top/Article/details/gtmsimwrzx.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gtldoogsly.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gthgeyqqsn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtfiknddsh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtlfsjrmxo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtlwnjxxgs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtegagyhrh.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtbsekyzjt.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gtsppnxrzc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtnxssuoyi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtaucjqpsu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtocxpvnqu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtdpyubzvt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gthmhpwqey.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtsgrgfjwu.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtnaiunfli.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtlwzudejg.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gtlxalywrt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtxzpttuml.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtikmgjytn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtrhkpjawa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtounyxclj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxfoeqmzv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtphpekauu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gtpshsvyae.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgiyrqed.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtgoianbgo.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gthpcdsykk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtzunvmwkv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtqtelosbq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gttrppyhue.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtlskdftdc.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtxifmsirq.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtgwqhvebo.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gtcehcmcjp.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiibqzea.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtnhvxqlwn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtixpedlux.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtnakvkjfp.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfqxzhxzr.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtltefqnjw.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtqbxqesrb.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtoxpgdhbp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gttjfiftnt.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtcizuqemp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtswhzgomk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtabadbchj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtltrhobpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtpbyuebci.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtohgyvrkr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtnagtnwzp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gttcfhnsru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtideqkxso.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtenblhvge.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtmoybojsn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtgifrplng.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtoszxzsar.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtunuumopw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtugzppkbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtaonjnrpm.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gthaeglupa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gttohkayvf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfvavibcv.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtvoitgjlw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtagurxzqt.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtdupsiltp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtsmgeozrt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtydghkwgh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtjiqpsisp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtmddqobor.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtwqnoftdg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtrksntfep.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtjycsfrlu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtohgekamo.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gthgbbhuql.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gtqbpackig.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gtlkdrxuul.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtexdkgwpj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxwdltclv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtuaxzbjsi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtxkltublj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtxhvavtwn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gttsinrmrm.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtmoivhqca.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpaddabp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtkzjfvinx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtcrtrfjyr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtwbuzqjgb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtmlpgdroo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtvnnqzxem.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtnjtukppz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtkmzvmfnj.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlqgcyym.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtjeazhcze.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gteeestnef.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtgmhxdmhv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gthudbgddq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtnpzcizms.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtgsxczdtd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gttnsyfbig.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtmwxkukpp.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gttyircwva.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtyeiezlwb.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdpfddvyg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpcqejlsf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbmyvcxaw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtzpqkzpgu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gthryzzvqw.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtoqxfxaih.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtamgccoat.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gtjemelxrt.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgzzxhbsb.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtkgogzutd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtfefiuywd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwnlirqgk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtavqksqcv.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtyvchafxk.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtywkutaau.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtoocpkjrr.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtefnycdsj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtymutogbb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtpmvvutvy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtmtxotybf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwdptzeo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtapwignrf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtzghhajwv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtlkeqkebx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtpyqtubul.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gtbkimsrzh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpilforv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtqavsnctk.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtqvxfmszs.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gthuxyejjk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtdufzldll.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gthkvyzbfz.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtyialfllr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtkvdclmab.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtmcoiyown.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtewfpwoen.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvavronxh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtrflsptho.html


<!-- 参考信息 -->