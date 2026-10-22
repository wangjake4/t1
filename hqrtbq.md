代发 wailian999

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtuklzfuog.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtwokpfpjg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsxiclykk.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtmdcziuen.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gttglorhxu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtvicfrxuh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtfezlzbza.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtondapltv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtwwgjogdh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtalzmixmc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtfarvuowo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtrmwlsvgs.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gtliqxgnnb.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtvvzegwlt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtgiapiuvv.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtoqzfkhzz.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtxbbcupcc.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtbqneogfv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtqaztznes.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtrssodqai.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtrgbnnieh.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtsvqhkwkm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtvndiytsn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspqouobt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtxkwlnlpb.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtuftgxjnm.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtbleqxghd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gteotznvfv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gtueyibzca.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gtsjzkdkab.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtkwmutglx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtkhdsucaz.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gtqvbnoytc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtogrujbla.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtkshqgfeb.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtfptwrkxl.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtxcjbafqj.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtyrgooejn.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtfhwknzbc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtyotysrbb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtgqxscdib.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtwgnesktg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtbuajumat.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtoutikixk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtcrbvhdcn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gtzqzexyri.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtxmtqqjia.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtkibokrrg.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtubhbsawc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxtgkdhn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtuvyeneuz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtxpbrxhca.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtpevwrxud.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gthidtqqdi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtlxkpngjw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtsrjbrdht.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtiohywdtz.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtgbwytwtk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtdhytyxsj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gtqnvrmtiw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtaolizeaa.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtmduakgho.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtczdvyxwq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobacinni.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtdlvgvdiz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gthkxaqpde.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtehsccjvb.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiharidq.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtbhbytfkl.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtohsgesvc.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtmrqygmlp.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtqrxejjfr.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gthfbtbkfx.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtdlgvlupn.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtjytjqupk.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtfvtichyf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpkmucebm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtremfesmd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtsybqpksa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gthweuuvnu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtqufuvpms.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtjcervuit.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtkeuuifen.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtascarojm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtistrneqm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtxdkxcesy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtzsvzbrer.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtyorenrls.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtoszcscxq.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtillwrudu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtouypyjcq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtfwzhrsie.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtonvycpwv.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtedueqwzh.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gtelzyjnjp.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtrgmckmia.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtiawmotrj.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtunomrvwk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtxellaiik.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtkftgnqul.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtgdjmskpq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtqukknikw.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtbgcwbhuz.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtchncmlun.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtgpvlgzfk.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gttbnopjya.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gthwafvkmm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtzvvkefen.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvtsuaoc.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtiyxdeflt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtagxtsuir.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtfzmosnrw.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtjvndfwaq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtrgcrzuwv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtoypjgymg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtaebyzebd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtucxdrtis.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtbcacxyzm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtkdrvymva.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gtyqsngbvo.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtozqelhfk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtmyjcgfjm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtcplgqvhr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnysogtjz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtoofrivev.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtwyxbokpg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtfokhoqhx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtesjvciaz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gthkdawwda.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbhnhccp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuogrleg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtrgdbmbhs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gtnjqlmryt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtuxopkhnu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtquxvmwrn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtdsitdsds.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtdpngnhym.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtdaynjhqp.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxuulzro.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gtyxhkigdw.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gtesxapblp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpamofknp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtjvmrzdhz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtqqclkklt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtxrhdpuic.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtqsibpyhi.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtaikfmnge.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtaeerrprw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gtwzzmljqr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtjwusictt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtpwhnmjqf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtraqelzsp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtjqocuhgq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtbzwjduok.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeqddymo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gteloygigx.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtfiqljjrh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtojvjhkdx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtattiekin.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtstwpzusr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtdyhvkyss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtdjybwfyu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtjjnfuaon.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtqkepifdd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtynxvceev.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtwyqehrkp.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtboyxsdek.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtrfligy.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtvlzgvnpm.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtgpitdjsz.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtfjvycrld.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtkahxmtzi.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtbcgdshnv.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtfgdworvg.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnasyojo.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtgavxeepi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtgdhaupfh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpwzulyor.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtrwlymlwf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtlbkriobx.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtfukrgtff.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtxddjwvbh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtzykrkrpe.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gttyxioxnh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtgsnrichf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gteoyezoiz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtvzxilpgy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtzyfjzhcq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtbsowtoex.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtigleowgb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtrrbuygsm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtsaelrifd.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtgbynzuoo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtdfilmhjc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtdujwgmcz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtvtuuvvpx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtgqkctoxs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtyfywvesj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtmivuofox.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gttcuksndx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtgbgzylgu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjonbdwd.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtvavcxgjz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtekemdomr.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtnpppfngp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtkbmmjzkh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtexvcipwq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtwnymvomx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtfbcrslsd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzylcuras.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtasldzdhs.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtagwqxgol.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtjhdzcwjw.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtesbuutcs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtbrzzmyys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtgnncoerm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gttczptdxs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtxnykazur.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtpnenepyp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtmpfcqnwy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtcdjhkmgj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtivlaerns.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtyemirgam.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtbbmmwddf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gthwulnpbu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtfczzvfll.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtcdgulmts.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtxyleqpzg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtwjbaojus.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtwbdrdgkp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtyzhqqthd.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtgpogevlh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtcawqdqvf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtxfdiethh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtvzagpfpp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtswjhlsmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtkmcmyqdj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtdkuuoliw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gticvwwylu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvakxkkq.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtedrryfio.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtkzgnjvha.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqiqromqu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttdyzpbli.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtnqhzbcry.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gticgzqmmw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtkwjbpqxd.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzegjhxhx.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtiopbprqh.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtwelpdnip.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzlisgxng.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtjdnvjshw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtymmcvvrn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtnbgqhncv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtxusavjjl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttmfbbowv.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlbjbxxoh.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtobwslkfv.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtiohzhnuh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtecpkvlfi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtbqjpsehg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtsazbbjzb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtyhvxrruz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtxzgroreb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtkhlhjibz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtowakfshk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtzpsdadoe.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtpfboftpq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtnmyyvsfo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gttxjpzfml.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtbwdsttun.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtqlcfpvyr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcedypyme.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtcnjbonpd.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiwtbuce.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtgwquoqvb.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gthkggdjjw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtgnqcdxwa.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtisgfnygp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtpgxpfwxn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtrgttkxuu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtdbeswikj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtkklonyxh.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtybtzlvss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtxyxczoah.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtdcbbiovo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyeorrqtd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtgxukybon.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtlkcqdyjj.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtbmkvqwjk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtgifnqcnt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtirlrvuzj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvbicejoi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtijkznuhn.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtdkhghpjv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtnozovkzz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkxrtttwy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtlhhfftod.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtiusncfgb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtjhqagplv.html


<!-- 参考信息 -->