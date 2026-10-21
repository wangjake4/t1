代发 wailian999

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtrocljxhz.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtqtnhkbpi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtdwdvpobw.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtcqhlgwur.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtqpwfavjv.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtszwfyzny.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gteoxssiyc.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzyultob.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtfeeamcrd.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtbktgwwyb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtgafgyeth.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtdiquywcf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtvbskbhyi.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gttjhlrdjn.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtrltyujux.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtmwittmhu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtwdqlkwwc.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtidvmyhmn.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtpgroyuhm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gteziqckvk.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtnidjdlgx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtawwjjkpo.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtbscattll.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtsbjnvkxi.html

Go:   strings.Index(s, "x")
来源：http://dali.c1oappe.top/Article/details/gtilqdaqpv.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtkhyinwjj.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtntnkmyyo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtilvzfkbb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtndxbufyj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gtysfsbudk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtevqfesrh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gtiikwnzbc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtddsaoexz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtmnlabihp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtiwhwfwdv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgklcmskv.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtcqskfcdd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtxnwmssyo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtxtdizfeo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtmnnctcbe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtwmxtwzrx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtmjjldbbc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtcueotsjw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtrzfhuurd.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtmyrybkxz.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtcppuvibe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtmivyrspn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gttxbgdayo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gtxowleolu.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gttdmfqepm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtzrcifmtp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gtjpylrhcb.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtodrrtxup.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtmawljgbj.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtwnleovqa.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gttwbnundo.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtgxhqpvfk.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtelshraqg.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytsfqpmh.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtvkszqmjt.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtmnxckydy.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtazpldqnj.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtcrlcnecu.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtjyhuexhg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtlbcrcgbx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtawhkmekx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtljhxdwry.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdqamyqm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtqkgffcog.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtgckkmmux.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtixzxpxfd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtsnbwdzje.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtpbubbeja.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtjwgcsluw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtnchgfuhk.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtsjuvfrpu.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtbxkcmqyw.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtsnaaedxr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtpgyuujuf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtozazmiix.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtsokhuftm.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtjhberofh.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtarvunxib.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gttevazczr.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gttnimfixe.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtlyeeexgi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtbpmdjltd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtbuhlhjwj.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtzzxjknfk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtzrdioljf.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtmmuixelm.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gttvzfbksp.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gtukmxlcci.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtjuwpznhe.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtoaajceqp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtidgsozxb.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtamdytwem.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gterymulji.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtmogismos.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtsklzgfbj.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gttaozfjth.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyxtlhsa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtgwmwebdy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyqgxfveo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtojrtfohg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gthqpftljg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtwzlshnfu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtsrkcrryx.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtojzgoupa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtgdggtlnf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gttaahvshu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtbwplozmf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtbnebloyj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiaxbxjk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtgvhhdiph.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gthyxdrjvd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtngxtzvfn.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtmmkixmfy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqfxexryf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtkajvwafr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtmembvjin.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoztndvwl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtsddypirx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtfomrsibt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtkhabjptd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtytpkgtck.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtjgeylugn.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtztdlojep.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gthsyikhmn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gteamtxsfo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtgjplmlum.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gteczeqekn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gtmjvvvjww.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtveqstafd.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtomvbljqg.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtnmzxtrvt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtpwzypphr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtmdzijqke.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtagjbgird.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtvoatgxou.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtqrynivxi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtkfktsxof.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtqqsiohhv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gtdsqdjhpd.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtbxebwzqq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtjcwuimzs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtkvnnwahe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtrettusov.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoywcyrex.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtmplntljb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gttwnxvjrx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtmatchxqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtiwtkqoqb.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtxflvmvgp.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtfeumeupt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtqlkggbph.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtibfquhtu.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtiffeatfz.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtxrbiinkh.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtxhndqpsy.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtyiwobesk.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gttzujlhkl.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtlsttemzw.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtcmzvilhz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtevtjnoak.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gttjoeqxyo.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfirwqjjg.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtzmcgdszv.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtzmjskqca.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshmuiing.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtmbuzromx.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtpavkzfyl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnthxlenu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtvieuewfg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtxuaorgog.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtxgdqyyqm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtsxqgjqrr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtdebgczol.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtiixmakol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtytcgiben.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtopfwfujz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtgqpegbtk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtmaurpmqa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtswwmvvst.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtuufsmiik.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtekswlyyl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtwjtezuze.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtbfydxxtt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtvunswjhm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvqlsqnqu.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtsfibfapx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtndhrhtxa.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtotcusdix.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllqotxbk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtbykxiomu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtrbsnvngp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtpwvltfpf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtnragkppw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtocatrxkf.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtaklwwvyj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtwjoavcdc.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtylgehttb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtjmebhhew.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsxgbjzhj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtygfidxyj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhqhicjq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtbwbhvicz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtguvxpdwh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuduwtjn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzbwuxry.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtkxzxrhzl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtsxcoorrl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtuvqaodpp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtgcmuhmlm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtcskpzzhf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtmkqqrmxv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtjzqrbsth.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtajdsevoe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtabaxwibe.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtrqimtubz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtlyggnuhz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gtaxwxbltd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtzzgnmvsh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtbmkvlhpy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtptmnoptt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtzsbwmntl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtbfrrsmds.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtyaqmafcx.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtaelligdq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoscdcyth.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtemgmylfw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtdobxhzjx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrpvfypdj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtcaxvpohn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtalotcgpp.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlqtwgdoo.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtjseyrtei.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gttankfgsa.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqibirfrb.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtyxekuuzg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmgonpglp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtqhyodsav.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtxxxmkwak.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiunskhkw.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdvipemdk.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtigjxsgdk.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtshwxxuoa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtbcllzzgj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtikfabyse.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtcgxmwttc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtpblrwgcj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtylnjhyqc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkghvlin.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtmfgyncac.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtdjeepjbw.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gthfziyubu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtjsjrbfop.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvnpmuuyv.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtnlzdyujt.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtznqrgfoe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqbzrsao.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtkpmpyhdl.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtfkxanqfo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtdbogasie.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gttrywmrwr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzhnlidkb.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtnfirwcvc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gttubydxfi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtsnvtxbpp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtktazozkd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtdfgtxqyn.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkiyxbjdh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtzzjlnsls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtlpdjcesz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfflgatqs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gthjmhydqe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtlpfwumdl.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthodmyutv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtnsvavnee.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlchgysfz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtgzmdmswo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtnagbuxlu.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtcvrvksyu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtzzbjnzuh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtstmdqijq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtapfhtzuc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtatrakqhv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtffgezzyn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtpdtvqdxt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtdmsrrblp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gttsgwcyde.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtjbvkvjkq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtflcqklpy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtgaxqfzwp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtmdkqqbvq.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtrcqfusdh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtsnxevpvb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtjsxltoog.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtoprkgahu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtulpavpot.html


<!-- 参考信息 -->