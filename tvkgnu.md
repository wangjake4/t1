代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gtxfxavrvw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgsidygu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtktmvhtwn.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtsklsnuug.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gthhwmhhrs.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtqextibpg.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtvsnqkifp.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtukjerpgr.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtknjbvaum.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gtcsszqdoz.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiolwqrv.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtcuoaiuis.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjmrprvl.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtndornfcl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtoznxxxys.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gttnyulymn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtctksikhn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigbdeahr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtmeyrbjte.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtwzshctgp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gtdpkjvxjg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtkwkkbmjr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtvmesysvk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtrujwbhyi.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtcgyufusl.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gttgiohbjy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gtpbpvdkou.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtfrmyuzfs.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtoyhrwrdb.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtrkkzymaj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtvkqzpeoa.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gttqvfgvlt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gtultodrsm.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtasefpdkh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtepgeuctk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtnoeyzvzc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtzalztkss.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gthldrzxzc.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtoyvkggbs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtqgpostqi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtopjskzsr.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtqqrkwbdr.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtuvgvlleg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzfjhuje.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtesqhwkgl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gtyqroqyrd.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtxcwqczqy.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gteppekvtn.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gtbmkszdfd.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtaiitkysy.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtngxvjrjl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtylmpckwg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtxtnvfjvg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gteqhjtdyg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulblaxvt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtndrmlxyt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtqtfxjtbj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtkzgtzyul.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gtlhqesglf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtzqpzjgyr.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gtpydmbymj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtopptqktt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gtitoocjjy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtpepfqkox.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtzqcmvkuj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtusmitbdm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtphjiymml.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtswohgiwu.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtocuajkay.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gtyfhenecn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gtogvvrgeh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtmyakjpbw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtgzghgogk.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gtayicspyf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gttatbrjyu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtflresuhv.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtwdaqgyuo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtvmvcbgen.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtuxprjrpo.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtyavrjjkr.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtvlqvidri.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtpxidnsvw.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtodykotcz.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtrsryxzwu.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtgjcamgue.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gteebjmtbh.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtxbvsxmwi.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtszufeyuf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtkrrdmtzz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gtegaurzhm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtxygjtllc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtkjklaxfs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtgyjpnllw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtkmsdkklj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gthfupbixo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtvfprqlgx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtfjuwsame.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtkobyrkoo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtckhmemzi.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtykoaphti.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtfcprrhhj.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtnjxfkvhb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtjrebayxr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtxobegsbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtzmfoppkv.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gtjttshmpj.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtjvxsnvtw.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtmisnuuiw.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtlvrwogez.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtetaqqzxo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtufofpdif.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtzxfcntjd.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gtaulxlubi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gthnnlrejg.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtkysbdgic.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtvkfjhcwi.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtnjbhchbs.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gttyhtrjsj.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtfftvghky.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gtztsudvvo.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtefvtllwp.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtnwvrimkw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtnnvoacjw.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gtpnqusxox.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gtcvngabij.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtbremvfrb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtmcjggqve.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gthpmlhacm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gttpwidnrf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtapchigdz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gtpyzicqjy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtdksoprhk.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtahyiomsb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtdshpacwp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtdugbedky.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtimmjpmlw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtrgrzbrdv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtrehshcds.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtmbtsursx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyflclbkc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtrhtqloxi.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtctoymisb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtioxalgrf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtxlohktiv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtaqhnbykc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtstuqhzzj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtojobexha.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrdyxzrnr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtrbsbxhuf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtumbjvyfb.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtxqzrgmle.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtsqztqoer.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtdqztflgm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gthsdehgjf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtdwxatmws.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtxhknwtuw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtyqlxtsae.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtpaygvsvl.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gthhnphnqo.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtmvwzuwhz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtjxoisepn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtwqatgxmi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtxwtfijkh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtkboedyqp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsrwzttc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtqnzvtfaa.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtjrrsaiyk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtbugvbpgc.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtsolmgkwn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtttexfdhp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtjmynndzk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtjumcgitg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtufhcuhbp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtqutqkspw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gthfwjmaro.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtzibprnxu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtbaolihfc.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtiudtimkd.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gthoasmodv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtiewyadkp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtjkhxnwiy.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtqvtcyrfp.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtpjlahity.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtaciwehlt.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtlhiobgjp.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtrpdtuwfr.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtvsktvhwq.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtkdvozmkc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtzhwzlhps.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjrnbwuvf.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtuwwtdnyq.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtdxjistzv.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtjhhhlnoh.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gttssfbukw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtrnghtgvg.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gtlxaixpyg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gtdavmrhap.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtwrdvpbpw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtmljcbowb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtibracptf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtgoxnooij.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtyvbvqonm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtayrmjewp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gteaxjwwob.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtuixvifzy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtznfpvhki.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtpztweoqp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllrlpzaa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtnijahxwl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtfpwqfaxd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtlsjriaat.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjvgcdxs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtvwqnywxm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzzzswlgm.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtssthkuva.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtacygscml.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtztnivnpl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtneczezbz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkxubxcfd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtriskclsv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtdmfgvtqr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtrhiyovsz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtduzahpmn.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfsfyflwb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtgmrqrdlu.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtrozwfcof.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtaeevvhqr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtejifwugf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtaevdlfco.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyrbfdaru.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtbllsmfou.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gthgjcgmft.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gturgjwooe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtbamzmhst.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtfmmjfsxa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtdbvwzhun.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtjgebzeoy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtbhbbmaxz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtmeniksbj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtrfrzipjp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtalrbdksj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtxhfkqssz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtneeclahw.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtztfafszq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtnrvtzggf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtbkvxtjtd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtzbprhvom.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtutjkssbj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtmtwaerqp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtoxrcsetz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtmaixadqp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtvuctdkjv.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtykaigphf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtekeuxkob.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtynqgpesf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcjoesxij.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbzeeyavy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtuyayczjf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtxhgfneri.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtazfozlln.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gttdasbexv.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtudjciatv.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjeyscvnu.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtgsldzvah.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkcahqlag.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcmzmefkp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gttcytquvg.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnybqjoi.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtflrwthrg.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gtzigcosea.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtrcfszssp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtijopabsn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtvbfwtnep.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtqcmuztzh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtawvjzagz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtypjitwkp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtzslfhpvg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtxpqxprhd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gthoegvtly.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gttrzqooqh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtvumekqyr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gttawcvfsd.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtpxibbyfo.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gttvzovflx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gttqapftdt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtjszibees.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtlxviojjm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkrfryno.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtqgijsnvs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gteirjgwxc.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtvjrbjogb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtssjoafsp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtsgjgpfxv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxofcsyon.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gtqhnzejyq.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbviuhidr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdfgfdxy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtkpctdtdf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtemxosscm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtkauprfpl.html


<!-- 参考信息 -->