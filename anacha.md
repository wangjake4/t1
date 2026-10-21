代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtbflglfjn.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofkbnhpz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtcojqyttm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtttlqgvvi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtkukfmuym.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtmlpyycnu.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtxampguon.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtnlzxzjha.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtmgoubpyr.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gthvbnzkze.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtomoakkip.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtspqekvhf.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtyokezblt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcfrodry.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtaeydbyvb.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtypkpqisy.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtqwcpfqty.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtqitdxlox.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtrlvzskrk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gtzacrkald.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gtadzbzlso.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gttnfdbbqj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtampejtkz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitjehttt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtjjxoyidg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtasfhzfat.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gttkkwpyam.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtskgchhem.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gtikntxnem.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtjhxlbgvb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtswxpzqjy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtgwryzjds.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtutuabyep.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtpjidkeoy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtwiiujhaf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtvuzcpami.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtewjnfjwb.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtmxgyziwe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtigkhykna.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtmbrbqamq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtnpxcdeok.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtqpovfxdl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtcnfsxong.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtsyksqnsp.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtknzugiyb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtehudegdc.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gthcrzwtcy.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtkuzmrkbf.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtezcdyrml.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtllkqtcsn.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtcnupjcvx.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtehzdkvgp.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtywfmutwt.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtpngicxsd.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtpokuuldm.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtvbmslbvx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtvojhekyy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gtjojulnvo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtygvonega.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtwdqncfdk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gthzpkboyh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtkehbasig.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gtkfivzpnc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzvglggm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtdjhcgkom.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtmoxnjzre.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtljpvwcnn.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtnrwyioux.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtirjmftml.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gteanjuqhx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtmhovexpn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtajwcrwak.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gthqwyqxtd.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtpqgfmlmh.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtpwliqfnd.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbciwnxxo.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtyvrzaidv.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtrfjbnbcf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtldxpovbu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gthvhfaqav.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtokjklkxu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtigynmicp.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtkfzvmszg.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtyeqekmui.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gtjqherkbw.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtmsljsnby.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtcazilrau.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtnkjosrpw.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtumtcneis.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtvbqjngpi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtkzpdochp.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtoynhxukn.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gttrrishkl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtmgzmlidj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gttmdrguqj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnzmwgdm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrtldzoho.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtoilsvmto.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtjogcznxs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaurrhzot.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtggjgoijm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtgsuiumof.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gthaxpwclh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gtsmggavtq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtvmcmkxrx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtykdetoaf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtlttldyes.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gtxtlugpdp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtzujeglfk.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtnjdfejtn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gtfmdbtdik.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtlqmpktgg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtgdpvywzc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtgdljgxid.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtbjsclbit.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtjtlrgfya.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglipnnlj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtekzrcmmo.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtxnjbwlvt.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtwegxldtp.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtvjubcqho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtwqfzggmp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtyusnmnjm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtnkofiggf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtalpfvgve.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gtlatnpdzj.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtszyokrxd.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtayqregkg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtkunxyykr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtqxpdfmib.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gteodsucxe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwkxweno.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtagciaelj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gtgpvjuivb.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtnhirpads.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtecmgcvjj.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtdveumwot.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtnbxqhrxb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtdgfqicde.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gthibvglto.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gttcjoujia.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtwokttvkr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtskkciqmb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtzpvmjumk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtrrszuwdp.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gtvvrcxxmu.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtqcejpfho.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gtoudnqeff.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtgevterdx.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtawqbpjdu.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtgqlazdhi.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtbopvasvr.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdusrkbm.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrokxmrxh.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtbpghhemt.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtgfvvwehh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtbwgetync.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gthqvbwvqd.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtqwbkyhbq.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtjhsmtrbz.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtfwapqnqy.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtefppfnod.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtiemmdzna.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtvdqkogwm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcvmyaeg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtcnqjsrdu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtpyvtblkm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gteimnqpcw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtqmbbhzme.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtfeydrpqx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtvnfkjxal.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtregynhqp.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtiwoqegxi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtttuziodh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtsvzgeoab.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtprglgmmk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtkjiritja.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtmqleygmr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtnlueocda.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gtvabugdig.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtcejaujso.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtaopilrge.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtflnjdzze.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtywvqmowi.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gtqeoorxdd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtvlrdrngy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazzaqbpx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtgfeaveld.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtllncvqgn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgadnemi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtcnblwtew.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjiykqvzd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtfgsrmlyu.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gtjzusemsx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gtuigleuir.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtttgtrsqu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gteeufhbzn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhwcxvsu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtbybnnlar.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtpojaxffn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtzvoypkao.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtynkstcan.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtwopbzegc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtdjygjbwd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gttnsuwybr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtfcrepyni.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtlqffqkdx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtecfxnoyx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtxneruhku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtcnbznkzg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtahizrwux.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtwakjjnya.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrtlbjtd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtyjjaczxl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtbddeukcg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtrmgelzph.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmrvjagc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtgejkiiti.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtqjujjubm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtenaffqre.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaqejurz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtocyeqxyc.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gttsgisbap.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbtkngfnv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqfakezjt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtfwqxbmda.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtjqsqwlhb.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtyuqvicoa.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtumlhtcbq.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gteoxbdabc.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbyaiamox.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtjxmskukw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtadqvefky.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzfjtfdrh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtskcpsqwm.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlpxybpiu.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbqxxphbh.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtriwhawjs.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtdbkodhfu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtuofsdhya.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtheatvpnh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtpfqpddpe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtpmvxcdsa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtclrrbsjx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtqfhrybkp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtkhpiqwua.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjfaeyub.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtssjyilpw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtzukamvgu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtaiyuedrq.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtbcyeyovj.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtrgiizlbx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtnmmqfgcp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtqedovjlb.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtyueskbzo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtcbjtebsn.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtgggorync.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvzlbhjli.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzgkzdpji.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtrxjxgibr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtyiimxzgg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtcjynkbfa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtayvpxddt.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gteioauoed.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtqmftaofd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtiqezlaos.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtpbtpiwmt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gttyavvotr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtoenzdcke.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbofmpuzm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtlirjxcsh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtyotyumzg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtnjhuvavd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtbrlvrzno.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtwyojhzmt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtxhytnzih.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtbssrsirz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtizlvcjws.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmgrrcktw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtnmguazfl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtuuzgzywm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtleiebnsj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtuaicxewk.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtthevdeef.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gtaqxcjrjk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmgdblmp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtsdhaencb.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gthatcdyli.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtwdfjzwbn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtnasjyrqk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtwonrhgxo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gttvpeowzt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvpiumacw.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtunooflek.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpaigrcco.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtkijnwlmm.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtsecbjgwa.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtcnrxxfoh.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtqpkyncbd.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gttveqvrnd.html


<!-- 参考信息 -->