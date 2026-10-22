代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtavdjkila.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtvvjuplol.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmtarfme.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtabdukonc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtkwpastvf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfqlbrfi.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtacjllnuo.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjefsetmf.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtrjpoaxtm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gthqaowrrz.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtgvavgtpn.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtivlkjhyh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuffhplqt.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gttfjhcirg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbkajyvle.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtafplqxyb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtazoqvzpx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtyuhzkkyr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrunixqj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtvwmgnbaf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtqrvokqdj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtcxmlgryb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtnpqgnfui.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtxptnqweg.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtpmzgyqcy.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtghxikroe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtxjycvfvz.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtyfewuecn.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtrezncroo.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtnphwpbwj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtquocjibd.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtgfufkfiu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtapuyamji.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtbpaupffw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtwqklrpqa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchuxhesz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtsysfkqqo.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtesxsjbun.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtegorguha.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtntumpnjt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtuogsnudp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gtbrgbdave.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtlayvyezy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gthfkszkis.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gtjpwccxpi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtzuocjbtc.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtfmimekke.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gteeugjtss.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gtvjswdqub.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtoiaqofrt.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtnkhiocen.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtnqutfmyz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtrrlkqmey.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gtdqrolxne.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtucovubgu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtuxkusydi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtfmkhwcoc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtlufnugdm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtjdnizjrb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtfatgypso.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gtlclnietu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtqgqmwzjb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtrcwmitwp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvuohwmf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtettxsodd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtnllihjtt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtgfwkpnti.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtenypaxgd.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtihnskwfq.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtmxkjykxa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtngqdyrlu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gttivqhovz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtkupuhlsp.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gteyqvokoc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtsubfhfco.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvtcqbnzq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtskwoaosl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtxkhdgkaz.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtoycuigih.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtiyfkanin.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtfptaiahn.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtcwvnvbwp.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtgvayyqcm.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtebedifux.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtmrhnlboa.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtecveawjr.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtpzjnhqav.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtqvynslta.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gtarlxaxxs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gtnyongecm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtttccojev.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtipuqlygb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtswlmblxr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gteeqpozfq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbmtkunv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gthbegfnre.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtxmewzcni.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtzkrzhjym.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtsrkbkbjk.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtrcweizec.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtpuvucqwa.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtbcszhwou.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtptcbjjhs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtvapsvesr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtqgogkhzj.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtiosfnizu.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtpvyriwij.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtlqqjyqtl.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtfxubfkmr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtglmhqovi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtjtxwbsaf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gthezggfij.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtdtzcnbpg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtqvxzbonb.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gttlybapac.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtsahigqpv.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpifhkrhk.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gterdplghi.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gteaxyvbyn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtsiqrvhgd.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtuccxlnvi.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtjepdettx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtjwlfdgsr.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtiehzdble.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtoionsveq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgqhbuaj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtguiclbzo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtyevcjlnk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtciavwstt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gttdbrsvki.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtbojsurtz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtmzehxwgj.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gtbflvdeif.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtzaakwmbf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtzuzqokaq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gteouaqpfb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gttilfpvmb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtxgbsswry.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtwhtuaxmz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtddlfbdek.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtvlrayqau.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtbunajtap.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtwdvnlifd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gtlexpxzmz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtvdspiwxq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtoacbttqm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtaytcaktp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtpscxnxcr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtkkqhwryl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtlqobqbbl.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtrijpnyvp.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtbzgvnlmy.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtoytcibwa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtzcdxxbqm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtxkyxlctz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfsvgaqb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtlqgwxgkk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtxbxcktdn.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtmsvbzgwj.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtlneqqnze.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtlhpvvule.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtxtjsvjym.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtqzeohxpz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtohevmseh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtmqklgbyh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtigdyrvgt.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtedykrtuo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtumslerzu.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtigpdywhf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtixwecgxs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtifyffxab.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gttquqdean.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmbopyrp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtdtiqncwx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gttlyyyigi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtboeuphwz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtgmexmqil.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtkqhectyu.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtyqcofqge.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtpzvxosjs.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnafosxts.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtasrsjevz.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtmbwzglkq.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gthnmvsixl.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtzbbrrhtj.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtjenpuwkh.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtbhstmtqe.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtwiakeoez.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtmaznscmz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtakfcpoxs.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbklbmpnh.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtgcvznmpu.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtbxdafily.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gteqdlvjyp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtivwcssum.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtonaxyygs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtlmuskbmm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtbicflkek.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsdsydyt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtkcqdaeaj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtdumapgzw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtovhfcbro.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gttdqytjzs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtlucwavwg.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtfzgrzfuc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtlodlpofq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpvarowo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtbzuytqzy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtrcmeegqu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtciflntmc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtbotfikwm.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtogaewxtc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtqufwlmrp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthqzgovas.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtukcmxxox.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbvesbyui.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtjdsvghwz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtfzszmjof.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtlsyfyinn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtxrcffddv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtasrapnjb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtqmcbjgky.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtemrpfebr.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtmsqzmzai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtbqyobrir.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtoxydwrxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtfyzxbdpp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtrxbixvbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtwdvgwcup.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtahmaivqy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtkxdsqawt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtidmykvwx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtpixunxhm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gtyahkhqbk.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtxsoqiukw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtcpsozitq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gthymwcuoc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtwgjbisgl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtbdcrsldd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtdxpjvqzu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtwefwufkp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtznzjtoxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtcarfjihw.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtdjfwajux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtqafoejmw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtxyobsqni.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtoqqzfifw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtjcdlkdkp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtgfqywdae.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbyuuuef.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtrqebaaoq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtcmcjutap.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gttqtsigjm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtcisxowiw.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtfrnfsanq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlnjhons.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvgkrbema.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtirevsjmb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtzbyxzsgj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtetebshog.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtucbgvkgh.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtymfhuwjx.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzmuyoybm.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtpyjuoeqj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouuqnhnd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtpayzpoed.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtbqppkdbf.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtquogqdkj.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdbmzbuuq.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gttcasdfdy.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtbvbbnlyi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtavrvrujh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtemvffurv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtsfpoutle.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtsakppgbg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtiypoqxjv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gtsdmxxlsi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtexufdens.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtqygzjxxh.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gttncpausa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gtbccasugf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gtkhejzlgw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtxqawtpuo.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtflgdmodq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtmlamjhkt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtfbrhugve.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtowxdjzla.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtqoxxkjtd.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtgwujhyss.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthuquselu.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtlrxwlfnf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtevyfrrjf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtmgvvdwtn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtyatyfcli.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtpkrqkblg.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gteopmbqux.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtatvdoylf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtfsyqheki.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwmzqwehi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gttptbclzj.html


<!-- 参考信息 -->