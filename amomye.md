代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gt2cgwegmko.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tevwlzsd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2bdifrqgp.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2hwijdqnx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gt2ehdbbkqs.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckiolkpn.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2rtryjljs.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2sfblmoep.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2tdgtzaqv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gt2axfrmich.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2qdxugjky.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2pptiodyh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2repxxnnh.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gt2evdwwyxd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2oqofikul.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rorlmpsw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gt2vjzsybau.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2uftbiumb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2tyjhuvpm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2ffvuskob.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2iaujtnel.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdkvxmtm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gt2vrovewlr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2iflxednf.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2pcljmsno.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2abzsvdnt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gt2hpefwgqd.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2lcwptley.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2hybspuph.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbohflga.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2ghcfksnn.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2flahahsx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gt2plovjvtp.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2yjideueo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hojargmq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2nvksueqn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2ctisrjye.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ympwycco.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2tfiljyqk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmpqqtjw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gt2jbgdakls.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gt2cshfctwi.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2yvwevijc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2aevamsuj.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gt2chqifzwr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2gbzktgsc.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2uoufxcgs.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2kzqwtemm.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gt2yrrsllhu.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2tuqzxeza.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2ypmxdupp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2zyuvkkbj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2axzcmpuh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gt2yvdnxawg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2ejmdvjdh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2jdhzfxqs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2vztpnrmy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gt2fpxirmyx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gt2qzcidnqs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2edgypmns.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gt2ewamnoln.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2mklkvnts.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gt2vaflunhe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2ycdwenky.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2bhxpvrxo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2stbxqzwb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2zzjtbudj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2kwlbhbdj.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2dhhglybn.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwbmfifo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gt2kohoeqib.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vysndlnz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gt2wydldgje.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2ullaoupq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gt2pzkiqzpl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gt2ryleesqr.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gt2xejcovdf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gt2wmabmeoa.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gt2sbbguabf.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gt2pckbqrof.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gt2umdiejca.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2bxnaoglg.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2lniyfgxz.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbcvokjg.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gt2gzidzaid.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2hckcoius.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqxponwt.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gt2pnatsdpy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bbqrwqda.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gt2sowlrkqw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2vkwqjxrh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2lcuxhouk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zewmhopb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gt2ummddyyg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2jbpdzouj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2hcbbqtbr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gt2bfsxzhkp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2kbhvissy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gt2myjpnpvo.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2wbjcuwyd.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2osejqneq.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2ehyduvpg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2jgutcyzc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2gnjekfus.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gt2myzjhsue.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2edbewkhe.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2vwltpsxb.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imzfnlxs.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2ihwvhoyk.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oiknjoor.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2svvccpzs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2sezuoqyl.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2ykoliqdg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2ttpcczht.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2otxbzdca.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2zoiuswgr.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2rxxipwoh.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2gcvrsqnh.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2rgoexrdi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2gtdlxvkj.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkkgxavz.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2uspdrgux.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtcxjnvu.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gt2vjrrjnem.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gt2pxdxmxzd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gt2yfnknijf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2mbxzoqsc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2goblvnzx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2kidsuusa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gt2lmdffjqj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gt2ukqtbaul.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfkwwtin.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gt2ithgjtvh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2lmycfktb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2spaqrbzh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gt2dfanxaek.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2nudwpczz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxmhyivh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gt2doalrtdo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gt2jlqnfzfb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2qbyftxbf.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gt2yelfgwlb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gt2kaoujcwx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gt2jwuveeje.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gt2wkmjltvr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2iehwaujz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzsfprgi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gt2tgrniydq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2crvnqoft.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrsmlevd.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2mkogrgkm.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gt2lqzueuys.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gt2jxokfdmu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2jkyimzco.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2qsavytbc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2idmxdcvm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gt2hecprzjz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfauxxdw.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gt2vxoqpsob.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkhwmayg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gt2hfvdvoud.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gt2uroeayyp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqaijsjk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2ffdbsngr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gt2pcecgilh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gt2smdxceqs.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2izcczlhf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gt2grybcwci.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gt2cauvetvl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2omkbedib.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gt2cpknylgk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2jiskpkqm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2ijdpmgzu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2dvsxbbkg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2cniqmocd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2qmzfbvjm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgpnsviz.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gt2bjpaxvlm.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2vuoqgeyz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2hhraofaw.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gt2dsbtwwmk.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2gregczid.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2equgeeoo.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2ribxdmal.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2qybdhybf.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2yzudauwx.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gt2rugzszto.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjgpkvkd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2xqlqigmj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2iasukuvd.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knqzgemt.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2djgxhjjq.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gt2atkowdjk.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gt2scceamug.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2opjoawtb.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gt2xugthjgn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2cnipzxrj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2dbsgoait.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2cgpdqgoe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2hvpusryd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqbkskbu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gt2jyvadorw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2yhehdkob.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2bqwvnfri.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gt2frlfnmbt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gt2auoqeutu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2igjhwsrp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2hfexwntl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2dkcbolly.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2ryjkbxhi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gt2bfiqfcas.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gt2vjoyusgy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2sljrpbmz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2klzrejfb.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gt2gobifvsn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2zdfhepef.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gt2oydcqswj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gt2rgenhwzf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2dmaegjsv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2lmmpgsaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2bxkcazsx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2ufqzrfom.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gt2rujaokhj.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mzjthxao.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2gwodaljy.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2eqvsuhmd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gt2qwwzfxor.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wstqvdvd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2caoyeqim.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2rswnwxov.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2iqzstgap.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gt2owxhloqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gt2tswaksod.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gt2wygfwafc.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gt2qqqcqwlg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gt2cvjyixfq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2omiytvmz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2aimxqysj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2zkqhcbtk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gt2qcxpdohj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gt2izkqgots.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gt2cdcoieut.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2mfcgpghp.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gt2aimvvnjy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2apgouhkl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gt2chgkczwr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2gfzfiogc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2yarzjivd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnxluasu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2whswucqq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gt2dwgbierh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gt2qwvrxogm.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gt2eutcuhks.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2nwytupkx.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uavriknn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2wasfvepe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2foqntuem.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipwjywqq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gt2rsgtbsou.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gt2wmevykjk.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldtadoha.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2bxpjuboh.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2icvundvj.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2fvzmuhab.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxfpxxgv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2youenxyl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2yrkpufip.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vezhwxjw.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qwwpgtdd.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2xjruzfja.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfomsbho.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gt2hdslwpkf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2coynmphm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2olkhksef.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2gvmbjzer.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkldeaxk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wblmbgpb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gt2swwkplsp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gt2lnlgzdms.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gt2hemxbwre.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfcxqliv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2dqlnhffo.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2qqgxzkdy.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2nsxnrbvl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2cbxigesp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gt2buagofbz.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2ukgrhffj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2txenhflf.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gt2drreowsy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2gsbqcubp.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ytsjdqmk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2eyvhqzyy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2hicxmhyl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2ptxtqocu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yngffnpx.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2upncwjtq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2ksqsrdba.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gt2jpfiitez.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wzazuazf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2jsruoqvj.html


<!-- 参考信息 -->