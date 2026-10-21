代发 wailian999

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtntsvbfiw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtibprbvxw.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtysokxalt.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtakxpiirq.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gtxkqarsht.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtkrpxtjdu.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtttzjebbj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gtvvbxxief.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtkugeixln.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gtvywtmbos.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqklskty.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtpvutfkau.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtmabqclzx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtgjdclyuc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtwfhskbmi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtmmmtjaak.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gthzlpdaag.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtkptzrfah.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtrwsuadgw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gttqfgafdu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtjccvlbhf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gthaggplef.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtnkiufbnl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtpgdxohrh.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtalnocijb.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtjdcxbbwv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gtaaxpjdll.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtpbjojily.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gthyomjbbv.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtoumdjmgj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gtzptyniso.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmsnoejer.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtgbpudigh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtxoobvico.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtywduwpll.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtjdwukqjx.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtutwiutbg.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtfwulrtoz.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtzgnjrvac.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtuzvtuvbd.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtythwcwbn.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtzduyoeom.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtxdvjrvsm.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtsfjyeavq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtwnbvlyoc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtgzktgojt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtfduatmlm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtewqvqtvu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtiajhgrqu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtxjnibosz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtlrhmtxjd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtmebahmuc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtnvhyolav.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtjikxpthr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtxudvkspr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtwgruvisu.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtgdpubyyd.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtjqrtnsbm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtwwxxihdf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtkvdvphyx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtsmuszbny.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtdkgvelpc.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtcfsbfneb.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtohibnpiu.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtnddykvrd.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtuydcfoce.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadqqsmqe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gtylqtspvr.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtfqtpyryo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtopxbwxqp.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtqgfjcwzm.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtjawxomhl.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gttjiwnfdy.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtrxunhdhv.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtmemkxfim.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtfwmwermq.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszwclwsq.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtfjcgdsfg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gtjdilayzz.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtqsbknufp.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtbipakvyt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtpohnkjrt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtbsagqena.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtbdujie.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtljegelvu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtpwsuelwx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtqkzcjfoj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtzwsvxgnu.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtougsvpgb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gtrjuoplag.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtepurrozs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtsfdlruwk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtquyzwjhv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtofpivhns.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtwrcxoveq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gttalfsfal.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtzdbcxbct.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtehwgoout.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gthovtbeal.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gtupabmgcf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtesvbzqqe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgkeoopx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtmcbabcyg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtrmkfbktd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkvjypik.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtgxvdatvu.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtojspzmoo.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtklnqkmrk.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtimfojsas.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtyrfupoai.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtdxozmpef.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtkpipmjql.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtvzyhtesk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtimmcdqps.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtwbnwcqem.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfojqjaa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtjaisihtj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtxvvvkgvu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtsvxxuobq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtzighiewr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gteacceqra.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gthhqisfud.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtjidtpuhs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtqlpszzqt.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtnyvudcgk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtexvgwpri.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtyjexfjbq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtbowbrech.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnwoywue.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtvyaufofs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtzonymsik.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtkedpkpbd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtbtmmlpnj.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtptzmwbuv.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gthqdasdrc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtomanzahr.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtyuyzheti.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtubawcaft.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gteifurjie.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gtejduinat.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtgatlztrg.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtjbeiltxl.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gtuzbwvmev.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtvsogpwaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtvpocxoww.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgirtcdtz.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlicvnhk.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtkxlvbgvn.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gtmncsuxmu.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtshxwjgaw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtgupkagiz.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtkfneoqdw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gthstxyesm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtiffwjyhs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtjdqfyqqp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtiryfyvza.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtqqafofnl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtophdrkht.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtnpvlykze.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtlgnoiahd.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfsheuqh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtqslgueez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtkjycbyew.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtuisjcjff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gttrptwocl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtwolztgdb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtipzrhnkk.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtldnyjtks.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gttyvwhybg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtlwhpbsqv.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtwmhfsffn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgqprztn.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtoesbhfyc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtohmzykhu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtnkivxwal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtmrwfffcg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtaphangpg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtkgpjogje.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtdmchbzkg.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtytnseuvx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtmeqoaimg.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqicsuwrj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtflgroyxi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gtagfsqkcz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtucsnfgfi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtdhuqyvzw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtwwgceeue.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtocgbpheo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtcopygqzs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gthwyszeus.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtcvfyeoim.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gteavdusad.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtqooxmnqe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtcgymgcsb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnltovjmj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtdhuufvmb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtcpyhtigw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtggbnvhxn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtdspvrteh.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgmmweyp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtpbumhufk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtkncdhuoq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtcvnsrgqh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtxhkdjuzl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtdlphekvv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtmkgtjjxs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtmiodixfi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtcjjomiur.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtcizxrazl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtqytxouqe.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtyrrpbgtc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttpwucvqw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttrrmoeai.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtmnmpisvb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwrtxsae.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gthiqunhne.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtdlivwmpn.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtiflcbhje.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtuveilrno.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtfwdlxbgl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzagxprnc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpriqmsu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaixzure.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtumtkeosc.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrdqjhtex.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtbeixxeov.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtqoxxgqfs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtpxphlxib.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbuyktjv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtruhuicth.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtakabwydl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtqadfyieo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gthucfzbzq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtqmqteudi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtcvcbmefq.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtdvamvqyg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtpphoymmb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvmmyzcr.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtywgvseoz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtzivpobfc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeqrzvso.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtbncpzvrb.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtaikdzcpe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtiveowbkk.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtbajflzyn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtsixogeor.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtdqpftycg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtdvpnpvxz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtqgmpxfvh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfqxgpul.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtygmmfawd.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrfmhdhra.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtyhxbwfvc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtjzydgruk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtbxtoabyd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtzhuzxjbs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtowuauzpf.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrrfajixh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtipikpwbm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdeqjftdj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtatogrkic.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtusboalib.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtoexcwmuz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gthmhvwagu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtpayjkudd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwyrhkehz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlvxlzon.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtinskvjto.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtmwtgzjgx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gttzvyxdnx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtqswprklw.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtrsaiedzv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtfcokryhi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtorozmcci.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtuwkejnqd.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtdsfzgcif.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyngzyytr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gttwxjbwmr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gttvfatvkl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gtdplnukiy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtldliuyiv.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtfcugpidi.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtroiscgwx.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtpbatlvyv.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gthlgbtvpj.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtuyfmvdqx.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdcluqixd.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtsyczsmuc.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtzolrfpva.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtfnpjuwyi.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtomietzyx.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgenrqrl.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtewawtrfs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gteqyplhie.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtszjqtnkb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gthhohqgur.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtjjvustaq.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtfitaerur.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtjojuqvpg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtgmwrywvh.html


<!-- 参考信息 -->