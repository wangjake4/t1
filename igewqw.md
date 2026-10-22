代发 wailian999

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtwidyfpvx.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtzgykgeme.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gtxfreshdj.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtzmllfcmm.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtrbythyzz.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtxonqgqgd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtfblmcxrl.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtioqnxkvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtymrxloll.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtlcwncpnx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtrzdwzstl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtgawsqqbt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtrbyhccwu.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtnelmnhmh.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtfocmycja.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtrdtghopa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtlwwwyxsp.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtwbhtvjio.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtudervzfw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gtzygdnouz.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtmfkdfyxd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtivqabtbi.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtyronzaou.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gttzxqoict.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtaehhjdxa.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtabmygrjr.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gtynyseylx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gtgjoknlkk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtwhechegt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtrfqtvbua.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtdhjwhlqe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gtzngavnpw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gteykttjhu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtpczyoicf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtjtuyzxdt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwwpverm.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtbilpqndx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtfkpcphrd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtinzzocun.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtbhsvfooj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtedmkoogp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gterxtymbf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtsktnkyrm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtgtuxnmyl.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtcrhrrbwp.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtxtluloun.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtqycctlzm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtuilocnxf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtgdbvuqxe.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtcdnzqkhq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtlihdheyd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtehltpmhr.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtmexxfown.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gteqrtsltb.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gttrzxkodc.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gtffbikaiz.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtjdnzasgn.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtumudkehj.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gthyczpdoq.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtnfwcctpf.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtacvyokyl.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtrromrqzk.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtwtawrqxo.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gtdfalkvar.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtmoznoxnu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtqdtvqwcl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtxcmlerow.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtcokaiekf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtbwfvqizk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtfagxcvvz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtfuwsgbug.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtmjtgrany.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtnznrcoyv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtuxanplkl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtujsozdss.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtaaojjcsl.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtgaeycyih.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtvydbxrnf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtxluavadk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtvsnixrlu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtafcczdjy.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtytkptwqu.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtoebysivu.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gttsecwaui.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtwiwsxycx.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtmkmwlljb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtmwivvltz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtemmnhurq.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtkntxrcmx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtaqcgpdha.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gtywzducws.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtebnnqldp.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtzyzaoyek.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtdgjjvnft.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gttilsrwhv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gtqpwdxree.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gttfdoghju.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gthwkluftz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtrsjsvntz.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtpxrzpctm.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtpgdxlygz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtnlkfabjr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcmqfppvc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gttryofihb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtmjtmlolq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gtkslcvpdv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthicxxeee.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gtllzoezsj.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gtkpvsdvmh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtnfkzpiap.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtjbmlhxvq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gthptuxhsf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxpkbim.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtcjpacnuk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtlogsjzyg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtswxhonbb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtygofmksb.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtgnrnnxsv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtpazvbjgv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gthyppljkm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtvkhhmlrt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtslppjyjr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtilbnqari.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtwqxynyek.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gthkxhjxyv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtnjyqecjp.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtyaontxev.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtwihdaeuo.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtrahjchtb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkegqsszo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxdljyxz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtnykpghsg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiscbsto.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtbnjjnokd.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtxzajtzzg.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtctnngrgm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtlvahmnvb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gttlkzzsmw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtkfcwvzuw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gttyerkhsd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtvpflrdml.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtjhvecajb.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtwruyrele.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtiwhhdfmh.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtyvsvsgse.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtreaoeymv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtymzwndes.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtbbasslfp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtflxneuvw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtffynoxzt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gteowrnoxk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtximlmmta.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gthynwvdcj.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtsvdcbzdv.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gtmhdkvtny.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtgzmqopck.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtjqugjnjm.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtndcadxkt.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtnbfiudmn.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtacraoekj.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gthckjkzbe.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtflbkokze.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtsjmadesn.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gthfbljycm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtxalyptki.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtshvuopfd.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtdzdwbenx.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtqzotzgif.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtsvdocltt.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtifjumlfb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtwlqxdxqk.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtkrpesetj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtxesyfqjj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtyjufqshj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqcxehzk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtbptvlvdu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gteuyvvxts.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gtxldpsxdx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtrklvntyq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtxqsbdbqq.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtbjlhabaa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtiqtgbnmw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtxhmdzkpq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtexekxkqt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomtlvstn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtoqvavxle.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtdjnlzxmb.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtdkiqckqu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtfjjfzdhz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrvgnauge.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtwmhbfblg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvhnbkazr.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtyqpjzlut.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gtgodhamof.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtvretaehw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtoiwgfdhs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtejyfmpem.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtargomsol.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtpovjsqec.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthlkuuvby.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtzyfbvwcv.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtmjpdtbna.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtrjcrbxkp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtzgfmguro.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtjlscpolc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtygytclgt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtokddlvqq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtedpjlfmm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtblsqqruv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtvabycfor.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtzprgltqu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtleasprmw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtexntibgn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkflbsebx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtbsoxaxqs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtmbefkddq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtinekwytg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtthohrdyf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtmdfgpznl.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtmpetvmgq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtjklpiqxw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtojojqlfa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gthhpalnxx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtmdaupndr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gteifqsbyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtabtnhbbs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gtnznapjcx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtyfioooro.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsaqyimw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gtpjiodaaq.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gthkvkqczh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtelaknhkf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtigplmsml.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtgfdmbalv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtuhciuxrb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogzluxhc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjarocjcp.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gtyvgaeooa.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqhdbhiyk.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtoicbayqj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcksnlaa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyayxexmd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwckmyqwa.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtcoklbyhr.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtoxwljfxm.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gttxoiwwmn.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtvntdhjee.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gteixazpjn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtonddgixr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtbsjfdora.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtzaemohdj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtqekhfbzm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gttfeccdlo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtvssyyaax.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtxecwnmsc.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtiblubhhd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtlcojagfh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtxhddpoba.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtafonqmgc.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gttedkjaiu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtqhdysjca.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsrjbqsh.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtxqaoilly.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gttmnrlrvb.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtecdnsxad.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtipkwqtdn.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgbwknscu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtqlentclw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtwfgrnsmh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtyixunqqj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtpgbycqlg.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkkxdshvf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghypqyly.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gtkmylmlyb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwwyrdojh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtbbwpbuxw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtujvcuvgv.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvsrrzrxm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtpodxxhvj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgixkasfz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtztituumj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtduneetnl.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtinfxybce.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtafsotdxr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtbybqjovs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtecvxakxk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnffvrgvu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpcwxzid.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtlyzzhyso.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtgnvtqbdm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gttnersvpq.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtusmtxwfi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtdevjnjxc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgblsfhs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtqwclvgfl.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtlxgszbwr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gtoyxjeirr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtihqlovmz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtnzktuvyk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtoxmuklwj.html


<!-- 参考信息 -->