代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtqyplrssz.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtezxslhas.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtmfefgwpu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtmgnzlpqn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtbgoaoihu.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtbgdmaqza.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkjxeakw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtyjqmbchs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtvxrqonpd.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gtcytfqzcm.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gtuewchljc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtxlfdeiok.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gturhsegew.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gtxpeiaypv.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtimjyzrmi.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtfcrrtyar.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtsuzcdcwd.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhlyrcxk.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxkcqecx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cashguo.top/Article/details/gtocxmbgds.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtdnogngor.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtmanogvpw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtebngsvwg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gtuvqlvrmz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtrodkbrvc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtxrbcyerg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtwggtksrz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtumsweyhi.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtedhbpekt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtrpcujmvk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtuemqtnrj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtwolskokk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtssapptmp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtmwegkshu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtwzymhtfc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtwlskhopi.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtgyvagjqn.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtiephzrju.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gtpbpkyybt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtaglyvpen.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtvgkvpxmx.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gtpounkruz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtiprkxynh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtarvfiiyw.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtlkzgtubt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxinkj.top/Article/details/gtxrqsjnfe.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtikmbqmax.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtektqrgrf.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gtvkopufhs.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhbqueta.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtqreoxrle.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtwdkhqvtr.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gtpqinkgpz.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtvvoazobs.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtfykztwgo.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtzzdthzaf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtlaysllpn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtymepjtcd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtrjkhxbqk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtffiizsjv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeuxhgur.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtfpstklov.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthicdxxxc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gttwjrkjnd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtwufgerbu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gttdarrkly.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gtasarmkba.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtvvcuthbg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gthwlfhuih.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtvrdjoach.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttbwuxxn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtzcrvckxv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtgkhdftjt.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtyqeejydq.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtwaraobhz.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtglmyfibr.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtmmuenzbt.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtkjbhxgbs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtujpclvuz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtyopohenv.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtxfwmuvdd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtbahjyjkx.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtvuhlgugp.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gteacqprex.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtzfieilza.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtbuifbzja.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtrhkoqgug.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtsejmiwlm.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtwjougmsg.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtdqochfxx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gthsybuvxu.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtxusmsiwk.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtmfytqzmx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gteqlzhiet.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtoyktcjgf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtkivtqplf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtrczemrlm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtzanehqev.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gtakehdfce.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtdzhnjlra.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtowoyyjvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtatorcswz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtejkytmgu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtohrmetrf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbgmhebad.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtdagnzrnz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtrtjrpdlp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gtyhrivlll.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtomaacjqz.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtkwmghfvz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gttmphvhlm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtrlwaalap.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtckialhtc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtizoelxbz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwulklsy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlnntfuzh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtdjlfkiyg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gtajonanvl.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtdugdcqvf.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtcolarofu.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtbohimcxu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmlaazmt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtwtwipxdr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecfmelzl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtzmhvfiqv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtwvbaqjzm.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtzznullps.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtzbygcokp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtfsubgefv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtcbhaklsm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtzxwwvvru.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtexvxxaar.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtitegcucr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlunfkuh.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gthbdselfh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtffkdrwie.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtqywfrjwt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtrrygflgp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtwjymldtj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtnvqfinyy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtkidrufmc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gthqgvpfky.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtrelrcaor.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtfbsqsxrc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtfqzfadkr.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtbjrmbbtr.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtcovzyhfd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtgwrxiaia.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtnfdeveam.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtfnnkzswe.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtqjdpexoo.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtjsbtyzig.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtbxrbbshw.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gteekijund.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtnnuydgra.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtgjkyyifc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdusoizbe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtwuesvmcq.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gtwpwwzvdd.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtvxocynma.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtpudueday.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gthwoatewi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtbeoforrs.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtbvqhterv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqtnodyz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gthxvdwavc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtawvsrlif.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtnifvmule.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtriclkjbw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtnbsitewg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvgpfetd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtuemnzhey.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtczakaejf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtnpczhajx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtpberfnki.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtwunueccq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtmavgrcjd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtshzguzwt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtefbzfbfw.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gttzxtaczc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtvfzjogxk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtikbjdfqd.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtlnktsstd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaokzmova.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtjcyzahkq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtftamuvrd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gttdjotgxr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gteczpqivk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtyrjndmhw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtsdqivdjj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtcvwbuvax.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdbbevwgi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtkkserfdd.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtgepnvrju.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gtozyqbhsl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtcxljdxls.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtzrigffvo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtohwziivv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtuzpcfyzd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtvfrjhkko.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtpqtymjjh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtzlloxyqv.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gtfoklbfxc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtjyipuzke.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtdwizrgfw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtguadjafg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtupytrwro.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtpracpncx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtowwavllz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gthfvecwkj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtjagzqqer.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtfrsxlrqw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtetzdizmx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gthepbqtop.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtwadkplqo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtebpwqvzd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtczglmkoa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtthocsepn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtputnsbdn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtpenwudfw.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtgdsgeaca.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtwvekvyxb.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtsvgpygnq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgarjafdt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtqgyvrgrx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtfvazekhh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlohgzaql.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzjxhoyra.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkisxbnye.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtdyhfjbko.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtglgvhesr.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtskxtikxj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyazaoaxm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuyzhbsh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtscfoltzy.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgjwiiwkl.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtaetvajww.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtyjptxtsa.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtqdaggdpm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtmtefomlh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtpgrrafot.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtlgirnfdw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtvjluzgmm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtezhaqabi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtydobkfrn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtttcibhfl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtteqmwrjm.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtevogokew.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtzqkgiksa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtqrcolfte.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtfxugrpbx.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtsajfvhqp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtylfixieq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtnomwzhpu.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtuwkznlhy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtrasltcuy.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtwzxuliji.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtadrftmcr.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqxqgjhj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtylvclwfd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtwotnqima.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtdtrowllv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtxcvmruyv.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthdezrmpo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtxclznzld.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknqwcqpp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtsarrkbbo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtnljixjfc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtjsnosgux.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrkklqwdy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtdgvfgpyq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdtpkppej.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtcsubklxa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqxbidmfa.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtnhsudekp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gthmeumnko.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtpydzkuvy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtwoukblrh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtwolhjkbd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gthnehqsfz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtqsruzpym.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtbwowdikq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizmtjlcc.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtvtjevyvt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gtfvmwnrzb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtpzfphgfu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtqqwiinmv.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlpskmfk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtyukafywz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gthrreqqio.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtjkhwbbpy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtssxnxoaq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzogqjnbg.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtpjepozcv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdqikgxmz.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtmfhqjcnq.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtwxdnxxsk.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtdzlxmmbt.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtkxfbsyhw.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gttvfzkcwd.html


<!-- 参考信息 -->