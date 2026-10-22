代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgsksvjzi.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtlbxeawgl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfoccbwvr.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gttasayqxk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtebaewovn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtbufjwuiy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoyioxnv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtpmnggphi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbzlodgzb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.c1oappe.top/Article/details/gttdekduuf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjckvenc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gthmruaafg.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtpgtsvtfr.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtqfcyhshf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtfnsuxbzh.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtctpxwhti.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtvtwrkxeg.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtghyzugus.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhpbsrht.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtuujcbgsb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gtqsmxzwlh.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtuvlmnqnw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtwfplciev.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzpjalkq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtcmckgbuj.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtoukfrfao.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtuebfxssx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gttavmjhyh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbhmgryy.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtlxrxfztp.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiwbtnpu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtyqpttolx.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtkntwlndt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtacxjmcfv.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtxyzcyeyo.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtepmndbog.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gtccftinrq.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtiporoipu.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtgxbjunsr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtrdjdxwbd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gttuarwcpy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gtdkslukzy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtxyyrijno.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtfnjaxpfr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtvwdbovrd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtklunvdnn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shuidangran.top/Article/details/gteeeaiumj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtlwjvasnq.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxwsjgqb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtdycemuwb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtcnhjnuns.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtlozabiih.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtpkzzyqzm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpaiuuog.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtuzjsergv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtguochpsj.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtnqugwyos.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gtmcuspoua.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtkldmpush.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtowcepniy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtbgszihcw.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtyiuaarto.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtexxwwphl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtikidiagu.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtoxqezjvd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtsjziezdl.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtsscorrpe.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtvxuvlbqu.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtgajwfcrs.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtsdrosxta.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtadfvivww.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtsqjumkak.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gttlqzplrh.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtmuvybkgx.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtuocbzvik.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtafcgiezs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtceaxnbri.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gtcwfexnsj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtgjrkicxj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtlqwebhpz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtoslurudk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtszykzarz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtawmorkrv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtqjhjffja.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtijoaqtcc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtbuirhbpk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtryzuuunv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtolnppkdz.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtedntcpkf.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtuvbieuds.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gthfqvstdz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtygflqyzh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtwmccgiyn.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtuplxnigr.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtkqhnmyra.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtgsdajpbu.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtppkbjgbm.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtjiedherg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gttkdasbjm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtotgkoqqs.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtwcfccflt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtdnlmimch.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtcnkjzylo.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtmbccswha.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtcfgafwjq.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtolexkdfa.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtvxghvefl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtsxgnjafo.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtvrlfimrq.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdktwqxjj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtatsamvml.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtnrbhkree.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtwxdnzwgc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtomjxxcvn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtwyvsltci.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gttmkadchf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtrthscmiq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtazftaupn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtejryzfdc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtxsgfptrq.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtztggmqrr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtnstzeexh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtshrvdazc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtavxykijd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtocnpsqrh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtzrxfnpzy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrxyffod.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gtfklgjyjt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gteupznjpq.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gtlwfploaz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gttyoghthh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtiakmmcms.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtegbtswhm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gttpykirqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtaoqpmhbk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttabhkeua.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtvzbsyceg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gtbarnkjlo.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtduzezmgj.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gtsacjcmnx.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtuddqabla.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtyflltqty.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtbnyoqsco.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtqpvvzmho.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtsjpmqmmb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gtpdhfdfuw.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtenvsynqn.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtdeyocnoi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtqusocejq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gthcncgmtz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtxvhvkwls.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthemyagtl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriuynsta.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtazikehdb.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtokjqokrn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtuoxtcuye.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtbtijcizs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtquprzytw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtfonmafdw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gttcvjtvaj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtcnnjlwit.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtsbhzujzl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtiutpryvl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtjmhpyjhl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gthaslcrol.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gttbmwfqmz.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtavtytbls.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqwrrlbiu.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtoqozkxdp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtrbaseemr.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtozdqbzkm.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtdykswibr.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gttwyrxltv.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtultgmhev.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtktusppmq.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gtnvcvvkpi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gtlnjadidl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtuljerull.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gthoffmxuf.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gthufepgcb.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtfwqfihvq.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtjdnvnnzb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtcircrywo.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gtmcmjywde.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtobzkixvw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtouqjrjoj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtkmwkoadv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtsoinzddl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtbtzklwfg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtikwqcjoc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtehbsguob.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtgjpmnuxu.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtxkxspbcv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtjvobbmbp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtkcgmvgec.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtmigaktms.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtnstimnry.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtajangsmn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoqksgqh.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gteadnsphd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtpjnrayvv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbsdwfhvm.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtlqawgveb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsnpryqwe.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gttdvkcdgz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtjnefhenw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtezwpqsyz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtefvbvmqw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtbxngleph.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtcvlmuwld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtlzaawotp.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdltqtaay.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtvdhpkarb.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtldiocryg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gthlapaifx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gtouowtujq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtadcwyrpk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtrumxmuae.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gttcsxglnz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtzcqnjaks.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtzvpohfwn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtwixnbuwc.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gttvkmfnnv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtmcjcyiba.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtyyzqxuwm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtddtqzxrv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtonjgiuzl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtbywicwfs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gtqllaghau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtmhnhdvmz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtxohlkdui.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gteygleyfj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtuyqwaboy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtivedwllr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtepcmqxtl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtcxvknlvg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtyvgbmqvh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtggkeccaz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtexngpsgx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtbhdrvxsj.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtyzmryayu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtjlmuwhsw.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtmmazubbk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtsimohemd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtwjhwthdo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gthwwtgjer.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtmyeghrkb.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gttfwozjlk.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyidpycyj.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtaqrdpfgc.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkkahryao.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtttpdlcun.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthartodmf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtobsezxsc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtagdtgees.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtelxsrgct.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqruufolu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtsolfvfpz.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtouyahffy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtrsxooanu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtzhssytxr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtjwexmnvg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtdrthynel.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtkbfsouoj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gtmaxvobbi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtuunylxep.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbufpnzll.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtdzktwnhc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtfzopusgt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlegjhkme.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtsbcnxdjz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtrzjjaqon.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtqywekdzj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtxrbrnhit.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtvvcuneaj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtclfvtoro.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gttvqowlqf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtuimwitvt.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrmdkhnkl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtcujdrrdd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtxdbtrfvt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtftnbzdon.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtvesedzur.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyhyfxpk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtozmesxls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtccotayku.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwadpfsul.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtcqbbnkdf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttwohoir.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gturrtafpc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtagqofctl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gttveljrhb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtzevsjdzg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzenakzam.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtftzaoacl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtufptwxhe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtpbqeidsu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtuagnbjwm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtnrapxvap.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtcegjqbcg.html


<!-- 参考信息 -->