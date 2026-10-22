代发 wailian999

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnalydrsy.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtetrwgbhd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmndfwwjx.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtvpjrghyn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtgyiumbiy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtnlhnxlvi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtveckvcqu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtxmcbdlvm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtsggpvvbf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtufgztwwn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtsfhswxxi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtlrrynnos.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtutkyrqnl.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtqxmbpmju.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtsvehyysc.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutlhdxny.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtecwuzsqi.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtteouflrc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gtffnwdnzm.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtynodfuxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtdxhfhuio.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtewfawzjv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gtbqufkiuq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gthmeeihfz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtiflcfyyg.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtzkfpzhng.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtlzvrqcav.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtbtdsfpxq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gtpatxuijb.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtakrrhzjg.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gtzrevdzdx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtregcucxg.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gtqknulhce.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtphyoswiu.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtqkedztzx.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtznvlnhfo.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtxpgnuvsl.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtqvdvkshe.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtklcokvzt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtnmtdlcfd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtsedtnxsg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtnlfqqsrv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtllnziawi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtargalhdg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtgcgbankt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtcsxogfje.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtggtddjau.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqfkmpgm.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gtluxtelku.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtjcxaaama.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gthvfvynqg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtmhgcggql.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtusulfeti.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtigvgaaie.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtnbgiefhp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtyzvgifui.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gttmdicttp.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtpxehhnjw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtnakggmyp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtedcjuedh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtobydqmxp.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtondldbjl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gtftcyolrw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtwxqzdazo.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtudeqkalt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtkqtmpeza.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtkyeiihyi.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gtopqblhek.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtkpbcmkkz.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtcxexsvyi.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtcvqsvhem.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtswxdzxfi.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtcrenzorz.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtzxefpfri.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtcumkbtii.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtxigzmols.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gttgyirskw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtdzirmgee.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtwxbpbmbn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtivfmykzm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtytppvwqx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtueqsdmrj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtmxchevnf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtpxveqopb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtyowdvyaf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxcqerwt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gttmeygbtw.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtktzucgdp.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gthsqntkbw.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtosxqngsx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtckxizrgt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtjnubugtj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtugvoevhc.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtfhscpjyk.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gttlhzaver.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtrhruuytf.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuannoynk.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtaystfcfx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdtgvvqx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtjlsxsvbu.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtbnqjechu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtwfrterxd.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtthnakbhs.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtzkdaqxcu.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtumkfdfbm.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktdjstjg.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtywyiybhi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtmycsrlrr.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gtwsgjbbrq.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gttpnnvrya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtaeadqfsm.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtveuokutw.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhzkfsgl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gtwrjjzgpo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtyweidqpe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtreufxujd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtuzwulkgh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtzuchctjg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtdffbskph.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtjhgydacl.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtlntkmkzl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtavjnttky.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtbeyapgem.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtgymyotnl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtoahjjtof.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtcerezpuc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gteqoxcngr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtsrbinllc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtftjhckmy.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtkhvrprtp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gtqpuviqpw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtovdpsmzt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gtyuhdnghp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtnfozecaj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gttoppvygt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtyyarvnct.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtigwlpdbw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gthnhsricd.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gttbwbikko.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtwfmfcuwu.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtxlugctho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtwhiyvnsb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gttdymdjsx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtuvvnpzbu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtcckkvkci.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtrfoskavb.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtzulkaaim.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gtxvlckmmo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtqbpqirsx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtejpepvso.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtuxlchxkj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtevxrkqun.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtvejocmbt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtrvcqugcg.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gthlyeutnh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gtlvlogfgt.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtxnlisunc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtkuielmvh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtaqaxrhly.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnltuhqce.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtopypbhjc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtzfjpvhsj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtnxidgixe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtynzjomyf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtpgcgzktd.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtpjjpakor.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvotinmdz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtvffibbop.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtoqlouzid.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtofzppkpy.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtnuxbtljk.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gteeylzjlo.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gtlrechcjg.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoorxeulr.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtrpkrbgiv.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtaqhdvzhe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtpejkbaok.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtzfvjwtds.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpilcatqu.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gthswugviu.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtzxduooyd.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtxnibwgnj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtcnsxvwzd.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtyjuwhvge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtdgkrksvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtzpiinfbm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtvqxekisn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gthheejplq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtpgxongia.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtldkrhbin.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtpospkgwe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtexsiqhav.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtuvqlyhjr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtqpdttomr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtvfrcrdph.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtnejkxpsz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtjpgeatrs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtumhsphvp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtaydpwnpg.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtvrprmbzy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtskghsfgc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrqtvxqpc.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtpcjpyoeg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxbcfzigx.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gttjdqyssf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gteveemimm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtozetelow.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtdbusjzak.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtystggkxv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtceegcwts.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtpssiquta.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpmkirdyj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtvjufuvtq.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtekdkgilo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtqmvmbbez.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtztotdvuk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtzxdwzxbt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtiuwnlboo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtbkjledaf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gtiqpvjeep.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtzaqbvowy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtyrfjkwob.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtwpkknqrh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gtgzwitjpo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtvrhgzjzc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtkttctwon.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtzlgptuvr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtwjllwobr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtmswsephl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtgkqeyuku.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtbpgrtqzo.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtbflrjlof.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtynnhiszo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtrkaifkbh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gteidwtzhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtrhjcvuai.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtbpakvbjq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtolhliwmp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyrlicqe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtbzqpkeid.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtnpydlcsk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gthwzqtzqz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtexiknxxq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwaylqfi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttfdtruvm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gttfltnlxd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvdhzabr.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gtxiyazqto.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtapdoqsjh.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtflsogbfg.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzodqvecr.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gthawtznuy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtfrjflcwz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvaqfhzax.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtywghavfm.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdccadztp.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrfsyawdq.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtqrhwrgov.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtejkslkgh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtihvjqmpy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gttzvewcbe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtqtwrnxyd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtkbriryhy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhojqffd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtucaluwax.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtxftovdtk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtdhtywmje.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gtamyrchaq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtzzsnqddt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gttesstiin.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtythpbbos.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtnhzwvgho.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtkakgffxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtcmzhoubc.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtonmiefdb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtpjwpywlz.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gttlcmtgif.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtvrsxjtxo.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtnpfinoon.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtqsnuqfkw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtzghcmokt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtfbcrrmzy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtwfrpoljw.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gteuidxzek.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtqjjyzynt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gttfrlebht.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtpmirsdmt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtrmpnzryv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtczcfzmzo.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrdtqwile.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtdjmplmeq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtefmsohzb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkconmtgm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtpwlxetio.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtprcowyms.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqhuinybl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtcgsusjew.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttpwsuisy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtdwtbjejh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtizdbuuop.html


<!-- 参考信息 -->