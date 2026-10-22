代发 wailian999

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtyuvzdcvw.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtqpjjnoci.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtlfotqgmp.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtfgbxkhcs.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtlhbbzmdm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtulqpouvd.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtuomvagpm.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtzsgxbgna.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdbxgmhre.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtzpqoqmvv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyjrigxpk.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtyfqbem.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtqhegbvqv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtspryaxwr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtbqktoizk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxqvzimj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtegaqhpgh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtstfxplpm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gtayxwldzh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtmnbznund.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtqoccuobk.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gthvhjukln.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtcpkmakeo.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtbbstbbyq.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtqwxzqytg.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtqebhfcmz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gttiitmfpu.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtgabupdjz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtigkevwhn.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtwyztkhmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlxzuwox.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtecszqxfk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtwlwmeigv.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gtboszqvpp.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtxgquvnlb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtbmdsiqha.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gtuywoxkfd.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtxyaxnvoo.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gtmlswltit.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtxzymybjl.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvelwpdih.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtvmekoruq.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtguleqjkj.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtvfexjyxw.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtbrjjebyd.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtsuxozhbn.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtaioyjtqv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtzyquxqnv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gtztekofff.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtwgvotdkt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtentubapv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtpzhiahrk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtzizixqyf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtmciisaig.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtfdtkundk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtjcuzsykl.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtorvjmssf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyueefkgv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrbqkwdt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtljoudwcu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtsmzkakvv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtuqmzniqv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtkqmbways.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtzhlestbq.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtegukmphe.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gtybjcwdwj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gttraqrmbu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtnnzjxlkd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gthimyjoyh.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbpsoiar.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gtoeylmnxq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtbhtbbakg.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gteknhjtlf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtrfxwgiob.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtkqculelh.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gtmrmhajgb.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtfaqsnwua.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtwwsnhnpe.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtgfgpflnp.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtcuadgtfd.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gttfpxaiht.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtrevsfxyz.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtksrbevzr.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtbpjjvdcs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtrsoyvydr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtiwaajsre.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtfursgfgt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtkxqmollw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtgqbxswkv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtmxsvevdz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtmreyuijw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtpqktcdlc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtfyhanuno.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtsoyomhyr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtjitkzuco.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gthiimfeih.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtffnbfszc.html

Java: String.format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaljkuhsu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtbglpzoio.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtkawkauil.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtwpwlkuva.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtneviszhq.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtujmoeste.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtrmsoqbwl.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtlersdcds.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtxkdcqdav.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtpmlcnisx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtjnfneive.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtrxwvibyy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsytlivs.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gthlwuiqch.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtcgncoaev.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gtjjwjapfl.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtbyfxhqdc.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtgslvktgx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gthxnwjgfn.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtrkxuemlq.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtskoeikdz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gthbotqnvs.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtmthufhul.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gtpfjzgyls.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtactqyjjs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtrcluyzoa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtsaykmsmp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtocabkrym.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtfcxvgtfg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtqzmclybb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtnrbwsgml.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtqupctkaq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtabqyilyu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gtexsethox.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtzmoagvdw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtlvgzaupa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtctdbokql.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gthwgrfrbu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtshejztdg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtlowfpgww.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtxmgtvzpn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtivihuzol.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtsqjeckna.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtkzabzcju.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gtazqoifuu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtvjthraxh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmwblwkh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gttvoyjfjb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtjicblbis.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gthkibnflu.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshlyndqz.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtxciovvzi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtdoibbnqp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtyaeabtsm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gthlqpxnce.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtpzglkgmd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gthhomvnas.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtutdjeutb.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtlygehgrn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtoathycpt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtpqcmojxm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gthrkhomje.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtcfyafouf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtzuirkygl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtswbvfdav.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtesmqhncm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtdnccykoh.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtowdlmgkx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtehgnnanu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtatyqjegc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gthugvqmjj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtdxcfceac.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtsvxemels.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtzewmaeub.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtyqwmunvt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtkipalzuy.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gttoqnctck.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gttkhplfup.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqamknle.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtpluqqauv.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtiojdumvo.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtlyozlhhh.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtgpcbbgya.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtocfzqkjn.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gtkoaxadqg.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtthfmmcks.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtqehexoqy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtviuzsfnv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtwkmlbdwc.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtfkesxadq.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvojaprb.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtrdyltfdh.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gtopysmsjf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzmfjsrwn.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtllmphaxf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtaeckqcbr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtindhiglg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtypvarehg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtxvcsgwio.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtnkuimrey.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtrjfcbchl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtunxzhgjp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtfyhztfdl.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtsofwxhpi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtrbuinydb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtmcjkszvq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtxvpifhxh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtjteoudeo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtenummtqh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtgppelanb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gtfmtczosn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtnzsvazzz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgqdwzvxa.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjapclho.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmwnkcxzq.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtrkxvxeob.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtfwitixcn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtswzwvqcg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtqtttnvim.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtwusujgwd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtrfxgempp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtxoevsxrc.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzsazryep.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtkhvhjtri.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtiahmscvp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtuotqtccy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtbpqixavd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtuamjagcf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtvamcycxv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtrlspulck.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtlnjuqxzm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtcvvymsfu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtkzecgipr.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtbybbsdlm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtiybmhsbn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtecapqvut.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtyculopgm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtfzmchuul.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtebkjoebh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtegllojlw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtzbzakynt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtqywlnhaw.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtqatbnsml.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtqzwgiopr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtwxdodffk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtvhuobnau.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtwomfokzx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshkuqhgm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtzudefnlk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtiquhiylv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gthwnvfqbh.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtuxswfsnu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtewyihhsd.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwfqcoqok.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuiisnksr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtsojifkxw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrtpbhpmv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtniawooxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthdzrzrio.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gteasbhqxg.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtcwnrmzpg.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxgorwjvz.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtwldkhugz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtodbjtfrk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpycsaguy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtfeyhhkcq.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtqpyxmlty.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtlqhnafti.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtnigbehme.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtzganxwgb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtysjzgkop.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgauuylr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtulaczmcv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtdothlakd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtzowsjvig.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtpkhseyyh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gtnojnoftu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjbulrqf.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gtyamplnfj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtlfzfjkjq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtkkttujpz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtempymhjg.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtemfbygxs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtettlhxkl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtyjkrgcsm.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtphtztpxp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtbgipfuoe.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtqoylnjyv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtogxatram.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqibqhtfv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtlzvrdjoy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtcrdltdmc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtjaouqvrx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtsjyjezew.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtcnnqxdbk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtrxajvpci.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtkdnjjqqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttwucubrx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtwbsszchy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlxrjzvak.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtybdemiea.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtwxhdxskj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzbkufkmi.html


<!-- 参考信息 -->