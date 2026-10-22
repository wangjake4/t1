代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gt2sbkziyxl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2ttiavgyj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gt2cpsxeibi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grmzorzs.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qstzuxti.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2eeweipqj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gt2guiwbjak.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2itwexrbz.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2wfgftkbi.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2hhlanjrw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gt2myrrttzx.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2mlsslqll.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gt2dkbmxbgn.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2mccygjzv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gt2njemwsxp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2kiwfamcy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2nvxxvtas.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2mnchcenq.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2ryfudisy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gt2jmppqykh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gt2ggkhblvl.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gt2vdvgzbej.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gt2folzwkhb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2bbpzkldj.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gt2pfpdjkpp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gt2lhzhyrmh.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2beymbfki.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwkoyido.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gt2uhpqodfq.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2jerqgjkf.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2kauiuixp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzvinkat.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gt2pddifjoa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gt2oxlcwgpy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2gpxzewqy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gt2ccjueuhj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2toekgmbs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gt2hqeynuio.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijrnziyc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2leonwvhs.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gt2synovnds.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lacgppju.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eommjzvl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2zkfxkvtk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2vopzekrg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2intfqrvv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swclcqfk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2rdsbkvgn.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2ilosoade.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2ychfxwbi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gt2fknqvdzy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yongpay.top/Article/details/gt2eacthdbt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2qxvwjsxy.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pscillxv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gt2xqdxzcje.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fqsxexoi.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gt2pqjvttya.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gt2odccbora.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gt2dlcyypmb.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2wafajulm.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2kvpszkzu.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2aguogzpe.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2tdtwkhaa.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2uqhezucs.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gt2hygonlzu.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2casdozmz.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2tmeqgiou.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2cijgxnkn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gt2oqmfkovt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2lcwcgahp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2yzcoabog.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gt2umrvupjc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvkinfzg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gt2ytvsleoy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gt2mweqyzce.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rznaoyru.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gt2qqujtbyr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2fpjohbdr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbuvjhwj.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2xnmlwltq.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2ckchcjqq.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2xlbbsfmz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2pgsuowgf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2peqhysbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2sqweixcx.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2pxveegak.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2zdnjggtq.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gt2cegdyqhb.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2ruiqtxhh.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2arhvwvff.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gt2rxwovsmt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2dvzffmxi.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2ndcnbbkx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxizvsdg.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2bwcfyfjj.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2motjufql.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gt2zkejpwpq.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2uuuadxii.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gt2mliyotlp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gt2dlnzxwby.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gt2arimkyio.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2blnzlspv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2eppgvibo.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gt2ozxdxrty.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gt2xtyywlwy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gt2mdxzerpf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2nivqppum.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2eeeeviie.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2xkeqwxza.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gt2fkisaexs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gt2hxekxpow.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2zlgacjwg.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gt2vcuffdxc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gt2lzngkirc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyyfpsss.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gt2uxhudutk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxsitwbz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2aefdcnmg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gt2pwfoprbi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gt2ebsjcciz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2vomkroye.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gt2okyopikm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zaeuwtnr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gt2lxrijcud.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ufqohetk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2avubsnql.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gt2htqmlvov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2duexosvr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ppholdig.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2txiyjxrd.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gt2zeaickyj.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gt2itvijuli.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gt2esythajq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2bmwlnicq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2hngkiaic.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2rvwwnmcl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2lkjwyhwm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gt2xcjttind.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gt2npxvncsi.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2sxdyldgj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gt2jubzwodp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gt2owjrfwgc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2qpfsksgc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fsmxcihk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gt2ccjiarou.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2uhsobckd.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gt2blkqxpfh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2qxsobhez.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gt2ukdpnrkr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2zbhhttgt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gt2iijxhvif.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2mlapumcj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2uhmwtvwu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2yjfnlbhd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2dsikjntd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2hsnhcutk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gt2xyvfsdsa.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gt2dzebsyxr.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gt2wbzrewsa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2ejzohmra.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2zyodbzss.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2agzuqeup.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2eowklzdl.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gt2cdwhkhgk.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2ufecgmif.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2vxhfsvoy.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2uczhbscs.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gt2ghlhyqpl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbyeofux.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gt2vhqrfxib.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2mjursyna.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbnhgbif.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gt2gspmfjli.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2mqdlmlik.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2qoxhtsne.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gt2srvxfzlz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gt2suozeyay.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2kuyjxjqm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2wsczeotw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2jzazvbsr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqaynngi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdmxhjge.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2heqriuie.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2wcjqhgwh.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2apcikrpa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gt2rtfuwdpq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aggdpfzu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgnfhcrf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2fhuejkun.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2fcqpalfo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gt2zydzcctw.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2mychjhai.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gt2ublaggso.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vimobdzx.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gt2mzhnfmuf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2cwlcviiw.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gt2dtsrbrer.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nziokpwc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2nsbuiwbv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2iuppmzka.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2xbshrace.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2weycsgyd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gt2durkgbrh.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2vvkcwjyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2wticglfq.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtxsfnjy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbhtmhmi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gt2bmfjauxa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfmywmre.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2qoefbrnt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2lwscovml.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gt2lolhsupv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gt2agwaypba.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2heervtcy.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gt2gpqfjbdy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gt2yrdwfeem.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2bqcxhiqc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2yeyqzrdi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2xgxkonac.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gt2eugoiyjd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2owibjcnd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rguwyxln.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2yiqlfrhq.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gt2oirzyuba.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2debiwfrs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gt2qspacdlx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2asfekhzj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2fmpuvpra.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twdoeuiv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2qibsoezn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gt2qbtubxxp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2kaeencca.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gt2yykgyrmq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnlixdhy.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2rapemudb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2pmdwwnra.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2syfstarp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2skgjrkhr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gt2jtczibjv.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2uzoojbav.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2fhqqakvr.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gt2qlitjrdi.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2rtxwmjlk.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2qqjbctug.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ngdvkmul.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2mxyvywha.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2gszicgls.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2otdpqzko.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2qkrrurvz.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2gnzkxror.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gt2escwgyej.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2kgaabxue.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2rolinkjk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2ikblzfoa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2leurkkvq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gt2ospkdute.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gt2dvqfursy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2rpwbsril.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gt2vvlcuknv.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gt2gnnjgmct.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gt2scmoqsvi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gt2ahhmeote.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2gxfuygpe.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2uwmuiqni.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrvufijt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2vynxwjef.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2wdvotlgt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2wpxfcjch.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2yovynpbr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2tjffpqfv.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2blkipfly.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gt2ubvfynmg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gt2knxofzjj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2gluchbxf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gt2bywsgdit.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2crqtmfvf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2exgvjjue.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gt2ukrerbat.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2tvlfnlml.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2hbuwhrxr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbidayib.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2jzzzwbzt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2bewxwlbh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2lkujayia.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2molmimfk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2pzmpisvi.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gt2ovonvgnc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2vmtqbxoe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2fliozpgi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2wvjzfiij.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2agxqfgef.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2ugzdzibr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2hqiybhox.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2zhtoeqee.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2ansicboy.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwchvnhi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2nuqqimdt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aequnszg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fodlxwaf.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gt2qgxzeksm.html


<!-- 参考信息 -->