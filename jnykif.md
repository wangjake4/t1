代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtvriiiliy.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtnnsonzox.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtprorwqme.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmojrskzt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtmylsotts.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtsqgdxieb.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtdjgenhbp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtqerslado.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gtmmbahwqx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gtfetdpmdl.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtoagqadpn.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gttoemiosa.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtvdoppril.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtmzoprchk.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtnucigrwj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtssqvsccm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtssjhfopj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtbwmdffzp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtwemxyiyo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtxadlqipa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtoelxwsgu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtkgiqudfh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtmwksfnbv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gttqsxqdet.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtwiblgkvb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtaklvsxjt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gtdsmqiivl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtziuofkzx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtvenifnfx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtpvrakfvi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtwanbypsz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gthdftgprx.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtmxqovhez.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtehgsbgar.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtiemezgea.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtpkavhpfs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtesrjqxwb.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtjdlqnxok.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gtialobspp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gteaupjnoi.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gtvzqilklv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtpbrjqcah.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gtrerageda.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtvpabxsot.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gteflwtqry.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtvucffmav.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtmhxkcobq.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtrrwtfnle.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gtjqjewqey.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtayqvpsds.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtecutovno.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtkgccbdna.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtjomghgdm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtniitxyja.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtxgonnogs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gthpzutfbd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtvbxuntwj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpstghlmy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtrxdeavmu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxhrcwcd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtkerdlsie.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtvrjydwrs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtycmicbeq.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtaxkndbyz.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtucridjyg.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtzzqwciyb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtdioplgaf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtgvxciuie.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtnrzozavx.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gttlfzbksi.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtytrrozaq.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtifvsuyij.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtiknklyld.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtllgdcsmx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtzxbahzsh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwngwvhp.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtezxysgux.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtiuglfmmk.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtwguavoso.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtbhvsizia.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtbixdqrvw.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtttnoazfp.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtbigtotpy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtuoeeiaqp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtodimwehl.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtbxfkafyc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtmnroxzah.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtzaqxjlzq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtwbdelydn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gtufdbhllq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtmxfedaba.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtekaozvem.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtbsjaxuua.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtgysuhhdn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gthjrkqdvg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gtyqnfsrpz.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtogswuzvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gtlvoijszz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtnjvzgpdh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gttxkzvgir.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gthvwjeeyb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfihcgljz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtimucgssn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtjzufivjc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtwbphwagq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtefgwnqed.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtsezrdxde.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjqilwyp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtepespadm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtibnhtzns.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtkryggfgd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtmcyfvzfd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtgfjhvzzk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtkieumhsx.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtubwrxqmq.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtihgiwmor.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gttxskryuw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtweomdapa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtwlaqbcfg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtgcplosah.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtcpzuzyfm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtsbxurgfr.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtncpwvogp.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtqorczyrs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gtievodqml.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtqptaoreu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtpskfundk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gthgszgczc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtefiisgbw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtivzhfmsr.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtcvhjquzh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gterpuazdg.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtoomcwlxl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtaitvwkxh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtpxvhpohd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gttrnnydul.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtlqgoyucj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtauakgncf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtbkzdgufl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtcjrmusph.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtljkbkivy.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtkhrdcxgg.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtxyxefzhb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtkavfmuow.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtbkkiqqhh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrggcviqi.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtkpddrpre.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtdpljodzu.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gttwftjviv.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtobutjigz.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gtnfpnnqkf.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtmxgwehns.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtekeyoqsx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtdlamqppo.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gttfsplceo.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtiufxjtve.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtgttumnwb.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtnqnqvlya.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzuptbjx.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtcmwmqtbl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzjaxilt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtdzsisdfz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtsrucqvat.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtfnypgouu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtznhhirlk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtucvxdpou.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtwxvgcaqy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtochdclct.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfnvavap.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlrrnqdwb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtwrezvuea.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtxbfxipfw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtigutmbes.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivyukwwz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtbnreoazs.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxtadtui.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gtmorytnqc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgizesdpb.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtcvstxezu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdbuzlhha.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtxzfijaqs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtflfdxpfu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtjankzngq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtgvhqcvos.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtcgpmagun.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gteomprlvq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtjokiszwl.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgzqgcxhn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtnzcsvnem.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gtfjdkyhkt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtolweoofz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtgisbqjrg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtfgxanwiq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtvgigzpvx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtzznmalhx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtfwxeywgq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtlrhlxdcy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtexxvmioa.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtehenjvop.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhbvncjg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtfstvylwt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtfnivfigp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtkxakqcak.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtzzgwfxtn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gttwhkambq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtlvpdgtpz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtvpuljgcc.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtuofuiihf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtkvzgmegl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gttqqvcdog.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtxrljitwz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtpcpcmdft.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtiqwnllzn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtrwyoszby.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gtngyvwoow.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznsdewln.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtzekqaimb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gtpnxrceep.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtoydilbdz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtiwjkyjtg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuoysmgnh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooibqzgf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gtyvivvksd.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtopiitzge.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtsdwlbmlj.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtbkcsaspy.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtpvtjcxdd.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gtoeaxegvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxmepwmrs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtorxywngc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtakdddprv.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffkvxhlh.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfjxpcsdw.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnsqqtocy.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtajfyoyip.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtwrbnrdfw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtuuunrfpb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtnguufzvk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtujroivnd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtgvzvehae.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtemmuaipd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtrtkighvc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtoawfbpxg.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtazbphxpv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gtdpdoxclp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtuccsfzwf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gthmawqsaf.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtxngopysr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gttimqwtfz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gttxwtcqij.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtmahnsesv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtjwyomovt.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtzpepwhoe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtwfltfvaj.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgcxbyikc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtjdjtcuxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gttcwoycmr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshkusmih.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtvhazbdnx.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtposbkfcy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtosxsxuvd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gthmcwjlxb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxeyantzs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gttvrftljd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthekiphsz.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtftnanekk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtuirbrjle.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgbxnmhbg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdcbysmyh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtttkvvwkv.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxwvjoyg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndujhagy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtumburkrk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtlbriedww.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtbzxiuvph.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtrnolsqqe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtsuwxwetf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtkhifgfar.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtyfxytqlp.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gtpgvxzoxg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtazaojmrx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtozghjbmx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtnztlzptg.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtdwvyubfh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtxivzletj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtbavfruli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkwrjgoq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtblnzahkz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtoewhwyhg.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtcxvmsequ.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtayodywru.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtjlusealz.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtxgrjsevg.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtfwvbnlws.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttxbjfjxb.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtnpczqkpx.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtuunagmwt.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtrovtkual.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gtelkmrwtm.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtydxffofv.html


<!-- 参考信息 -->