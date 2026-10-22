代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtvscsgjjx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtvupudwqj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtwwsjqnkh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtzhgvntgf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtpgwxfthh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtuetewfgz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gthcxpsrak.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtuycudefa.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtmqcqfkpq.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtrxzmcbsx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtptxcvqow.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtfiqcoyux.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtqjbdhowo.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtcclalkry.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtuxfjgsaw.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtgmlnqpxb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtofqmxkmy.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtrqyltbbg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gtygswedkf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtiqcenmst.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtfpcdegkh.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkcsgskn.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtskgapmgn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtnmehxsfv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtwbzxrazb.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtyherqojv.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyxigepu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtuyjtaxwz.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gttatbcxdy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gtqwaejmrr.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtpxxxpkki.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtzbkffoiv.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtyxjcchch.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtobiaoism.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gthbzcsfno.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtpqctgjyg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtokmknyko.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtnezwbxfw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtewkdbnoc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtpsktglfa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtsanaatyx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtwprwzjam.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtfoyettkz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtlbsdfqol.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gtjzomnkcp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtugvmkwai.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gtctsfffrw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynwukoxc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdwgqdcf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtuqhymmwe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtomwmfsdh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtxamuvyeq.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gticdfdywy.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gttysbdshl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gturrzpjkp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtshjttazq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtmrixwzru.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtsnmclkly.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmqgageg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtvvwcvier.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gtfbshmlzx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gtyazuploc.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtxzadhmml.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtwitgdklj.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtrvtvvukm.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtetcrcefi.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtfczqydzx.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtzulgbyyu.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcfjlgma.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwztmlau.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtgmijmijh.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtydxjmhjc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtyukwpxzf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gterreoegx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtwrdkbulp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtawxgufmp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtyowckaeh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtthestgle.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtjqqtevoj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtudhkfxpd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtnkxjltez.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtgtqtakuj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtmifrsasj.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtvudlgjls.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtdddxvzaa.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtsuqylwmb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtglwlfyqn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtxjulezxr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gtnfpqmrng.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gttkibgeml.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gthdzludim.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtapgyyowg.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtirueoxeq.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqleoxyo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtemzjltcy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtakxlzuhh.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtszvkfpgf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtasavmziz.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gttrztpegf.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtzdrxzlev.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtyggtbxhf.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtwhoczcug.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtmnswamwf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gtvvxqirvz.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gticowltnb.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtsuzdzlhd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gtiwsrtldy.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtnaieygdp.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtsxjdtlnk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqpgaqkv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzccqgdzh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gterafaagd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtisdpoxvt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gtfgusvfop.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtsgdldewa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtlkodsqhh.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtgosqqaef.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtkycfdzfl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtooexyhlh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtubliwymv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtywzjufhk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtkmqymyrt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtsynrpqvv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtwnulzogj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtqepwhrhp.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gthslpavwx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtjppzxghz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtxbqrucrp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gttpbcwfwc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtdchsmkkc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gtbrxdxrib.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gteaxvjcvw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtmnemqqmw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gttfdhduoi.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjcfxweo.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gttapnbjlx.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gthsoyrzif.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbugrstw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtnjnfusak.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtqfshmsps.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtwqwwgese.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtstktctlc.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtakjymzpo.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhigzvnl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtwvtkinep.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjshwdkjq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtrshbukzc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtkzmeljiw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtsedetkdw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtjkxzrfnu.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtjxlcyear.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupecraep.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtujyacrfb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtsbcmhpni.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtqvyjragl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtllufxufy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtafitjakt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtwsdblpuv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtpelhafzt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtvbmhgtxj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtilvosezf.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gtntckudjo.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtjbxnjmul.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtkbdkmxua.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtcawdhxto.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtqiazvlel.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtqgqggehq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssuxtexh.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtiyqghtuw.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gttnoxmiia.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtzjlfswyu.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtedubdkne.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtooxbycpn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtyhsljhio.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtwlsnkeru.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtejvspktg.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbkjlxcxy.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtcxvqcdjq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtelphtrnx.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtdoiaqsgz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gthlimtqxr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtryphfrwh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtwtitdafr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gthcoqmqcl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtgioikwcz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtqqvcnhgl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtrfkicuxv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtoiddbfhn.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtliyztcnz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtgtmxuflu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtofijacov.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtenfnmjdj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtemdzqfdj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtpoysyrog.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtwxecevkp.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtgkqlqsgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtojlsrhdu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdqhgbdyy.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtudcclpdd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtowduyfez.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtsxcojrzt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtoopypqhn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtcczmocuo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtjkmoorzk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtafiehlzp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtrccpctic.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtophmtemw.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnixpeick.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtsnvyjeqg.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtpnigwtan.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfjrphol.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtadvdxomo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtvslhpadi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtmnzgkkoc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtvwocayxx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtkctjkvff.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtfrkixytv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtmclvfmla.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtdvmlstno.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtxlokvraj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtwwhazhpq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtmuhrohcr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtbihvausg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtfpkenvnt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtljbcqqby.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtbgyykkac.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtzxeocjee.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmfgjdvj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtlylsqzlg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtpfmvyqte.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtvmgfxfcr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtxzbissqn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtnvquqvak.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqkgsjdp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gthmvxsfwn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtprzbjphn.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtiougixri.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gteyodpeyi.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gteqysoust.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtgffpweml.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtonutahzj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtvazeohsr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gtwzxodtdh.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtuauzugyb.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttmohnubp.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gtvltiaubh.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxgulviqv.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtcohejzyt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzuepjqum.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrudjlfyi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtpjljqsei.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtzunbjpib.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgqyrfrzj.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtqkuxdywz.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gttansgfto.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtdyensdax.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtqgxfxufw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtwxzgmsrg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtagrfdxxm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtsyknabxu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtlqeechiq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gttklzgizh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtrxxwfpbm.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtdwbblbmk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gthzhshghp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gtnwjfhszs.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtzaecqjvr.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtenrxakzo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtiujspgnt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtpgzogkuw.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtmaksbcds.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtxafzqasw.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtxqgkxrft.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbcygegft.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtyunevkyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtmfymojgh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtyztvsriq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtcwhpdxow.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtubhgrlhn.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gthyiwmzsp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gtundyqhkg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtjuvrcnid.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtzdsgomod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtgienfbre.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkcymfogm.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmwveisys.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtptwmzkqj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtsibrbvzn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwonkxjmn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttfhfnbmv.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtbwsphmeu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzcrdltqp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtnsibctbj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqndfbkik.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpqvmpie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtsefikdku.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtexidxiti.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtiyjcmcdj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtnzjjvjss.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtjqhyfpym.html


<!-- 参考信息 -->