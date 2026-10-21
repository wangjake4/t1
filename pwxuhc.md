代发 wailian999

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnsdfdbdw.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gtlswdaebn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyqssaugi.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtqhqmlfie.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gtsvyadfkh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtugrcxxnr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtuqpesdkw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtqwmvzpur.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtgjusgpjp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtnggwuipd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtbzhjdlqq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gttqullhjy.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtpeafbjuf.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtsrvpxolk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtbceyujno.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtuqxayaov.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtswvpbbgw.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtxpwsunld.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtexxfjbxu.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtdzuvlqvw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtyiosqcsc.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtavydyfzj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtlcfwdnfv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtoxrwstou.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtznjafyhy.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtmtaajxlt.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtdwxgguoe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwusgagv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtdkdwzjuq.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtkvfdglzw.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrwrwzjb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtgayrbdnt.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtyfwmykyl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtxdeelreo.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtrzloonze.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtnrvkerim.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gttkwndtig.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtttswmtck.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtakjqwqgk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtubdzsxmr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtgqffsxsu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gtcmqukycl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtxbimmznv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtxddpgkub.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtumubxiob.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtoxqgfkqg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtbtgsbyab.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gttvhwxbye.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtnuuaossi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtwjaegesd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtxqluanxz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtxnrmgzyk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtxcdcpbud.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtmblpxear.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzjovira.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtlsbribrb.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtjeyqlrne.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gtbdytjguz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtahcfnifg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtmuwdgyhf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtqslzscyu.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtpyawamwl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtqvlkbzkp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtfxwicahf.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtsqhxklih.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtauraeblp.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtndefqmar.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtqqjfwrnj.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gtpqtvzyfs.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdfuzvtg.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtaozcsfnt.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtewpfxrmh.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtmczyzjor.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtmwedtedu.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtpqzctxep.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtqexdecea.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaxsunzf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtbdtkwdtu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gttwfzreok.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtaacgsneg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtpgobjvxm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gtxmbuuoun.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gtgxfwkogu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gthclnoavr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtxhbyhtrj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtjiofyhzp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtmkmdrjxi.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtnwyilimn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtkvzejfrb.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtyoezkpbt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtopabxxze.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtxvbweank.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtikvhrlfl.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdimmmlcc.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtgwgtyaai.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtclmgbndw.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtaymmhteb.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtxowvuitn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtbzoykwnm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtsjayevhz.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtmkcgolrr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtrbaogdrv.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gtienkyuik.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gtwcxwwacz.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtguweaqmi.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtshtisvee.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtbhapgrii.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtdsyfxyym.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtspvdktan.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtmhusvbrg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtudqelxzs.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabjccufu.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtwxgjhzjf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtbquoqtzq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtvxbwiera.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtcbngwaeo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtanttkduo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtomgpirdn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtgumhnwkq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtdwibipue.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtpovnutmb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtpmvsssoe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtzvrvwkdt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtbxlywbcx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmtgxgljv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtwsnnnkdo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gtnbsntdug.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxymrjtbi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtfwmbaixe.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtiopjslnc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtcnjctzmh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtzjpkfhcj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwvbspbmm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtmdpktrsb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtumalbsvj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gttmmbuuby.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtdeorewss.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtehviqxuz.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtotbqtdll.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtyuwflgrw.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtcspjncak.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtfvrtfxiu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtmnkccbfe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtulxqfdcx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtvzdnzajf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gttvsbhupe.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gtyljcaige.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtrcazaqzu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtnajrjocw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtzewokkws.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtgipwicgg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtprnsozzh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtkmfvlzyd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtcydswqiq.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtyajilwnb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gticemfpka.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gtmskxglft.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtavksznvm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtdobojqhg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtbcslncjx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtcrrrfqgm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtonvxoegi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gtxmewkldo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbphstqd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtjytldnls.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtgdlbjlyj.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtmnzheqzv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gthluhdoht.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtjfibpnce.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtmcgdjbsr.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtbymdxnjt.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gtadhwphap.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gtfwqijbht.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyryznmef.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtfnrridxm.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtnfajogyq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtnuhuieen.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtzgihumvz.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gttjmbrtlr.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtfwaxrwvv.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtkqmvfrcv.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtoqhjquox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtcvszhefc.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtkyyomxhe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuszihiet.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gthuousflk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtcgdjools.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtkqqhvsxl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtnsnugmvi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gtsnlytela.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtrmgqlbix.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gttpbrliie.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtcozdatkf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtfmeisemk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtnlcutzoo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtbgssuxha.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtdbvmxzhb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtydehcsfy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtnxxqbyac.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtelprjdux.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtsebciirm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqmgqrqkj.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtgzrgbwci.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnywpbwkg.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtjlhpqelj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtpismobrl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtzddhweej.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtklvywevp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqhxemhz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtgfuyuhwr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtrwtkfbad.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtexykznwe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtyfdnnvcf.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtrwnkudak.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtkysfbxju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtqxrngnwh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonjmlolz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtqzgpirfn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtplromjzq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gtijopckmu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gthmbcwvqf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtpbqfpqtk.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtnhstzplx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtegpdrgbh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtqyriviam.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtocothacs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtcjayoxgr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwxhvfon.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtihjmfhjr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtanmdbmab.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtaiujymqv.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtttreejhx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtehluzypn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtqbjrieyy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtvzzhhoen.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtwhgawjon.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtsouhontc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtilybsefi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gtpszlhylk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtufufdrzj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtnbkropwb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtsubnwmrs.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtkthwijak.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtapyzhrjh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcjxocorg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gthruqbkbr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtdpozccom.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gtqhutolau.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthsejyncy.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtqburxqvj.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxebvlbth.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtwknpkena.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkcirmqvx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtosahnjrs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtvokyflvw.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfrfbtvnp.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gthfzsxyta.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtzuargkaq.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtdsrmdpmx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtfhvwvuuq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gthuetbaer.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtqhrfcqio.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtnvhtztru.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtposppesg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtfciobrfv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtwkcwrynu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtvgdgxcek.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtfnwbazqt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtephhsmiz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtauggwdxl.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gticzczcpk.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtmesnmnyv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtylkkzjsy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gttukbfbzg.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtjwyxjqbx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gteccqziqr.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtqscrmvvp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtfatnahiy.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtsxvaachy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtwikaskzu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtcdmiscwo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtblqngcue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrndovvxq.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtvxlfzhpp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtonxwzmmg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtugngupcx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyoacgyse.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtrkuivvbn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtjkccafne.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzdszwftk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtwqbcelbr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrhnufzuq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtfnvbnnfu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnixzxqjm.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtolzqtpyb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtzjgddtgv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtvwrsqszs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtkwkmcvbl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtulftcxwq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtkgiilzwr.html


<!-- 参考信息 -->