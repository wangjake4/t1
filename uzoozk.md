代发 wailian999

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gtdincuxkb.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtftdnrfws.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtytldsisk.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtdkhomcjc.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtdzmkkvqx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtripeqmor.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtdtsgwvka.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtjouldrhx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfxtleijg.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gtboawwxxw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gteugjejoa.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtzkiehumk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfxcngfb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gteiknjxfx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdunwxfya.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtgjqzalok.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtqknbybnm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gtvohuouni.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtrcwwkcpj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gthsqmunkh.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtdjjkicxc.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gthmuzmywy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtgdinhmqt.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtjtagafzj.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtuipfdsrs.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtgtwpvpax.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gttpeiahip.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtustgqhsz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gtmnsyztpe.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtnupdpzrn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gtzhbdyujv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtjkqtznbo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtqxbbjgvh.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gthmtpiadg.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtwyhbkfpn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtduwlsapd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtxtrsojmi.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gtomhbflrb.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtyqmnysns.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtvtnglajj.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtssenwlfj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gtyvswhoub.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gthlqvgdrb.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtrmvlgyiz.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtjmhkehtd.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtzfylegay.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtfchtpnwt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrelowbjt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gtlmmfciqd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gtnvypzyeu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtnqymmfww.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtgaqdfbuy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtiduznxbj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtuzxcziqm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduhvhzdl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtwcwddtaf.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gtbryjhifi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtcowtwyol.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuptcnuqz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtpxkqaizr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gttgaqejtq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtauwvckcm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtusnpdpns.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtmfuybsiw.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gthajymitj.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtchcrfbps.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgghxgvmp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtncjmlktu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtwebrllfs.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gttmwnnzcz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gtslyxpcfy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtyaeuocls.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gtoggpsami.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtqsoodrdh.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtlglbbmea.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtlmbvsjka.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtppbyahxo.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtvowznbze.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtxtwoejnc.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtjrojbisq.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtjhjpjwjn.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtwpqwcdqo.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtqytjhcmm.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsftbkuvz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtfhmjyyoc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtumszhvxe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtaxkpifgm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtoqhchmea.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtdicmyimt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtecjbkbry.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtztxoooxp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtukilgbem.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gtbhawnbae.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gteknzjpgl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gttpmkxatp.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtxfkiizit.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtgfcwrauv.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtugtyzivc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtsulzwvmb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtgrxacilv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtdzqpsism.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtugtpuyrt.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtyglmrsea.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtvzguzmwx.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtzwlxxpoe.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtlppognld.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtzdraohae.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtbechpqeo.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtnzbtimqx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtniuuevar.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtnxonmqex.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtanjwdcyd.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahfjwohn.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtwuqknizr.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtdycyubgm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtqptgruxi.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gtfhkshggb.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtwftrvkpe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtheiiwjgg.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gteoqstbli.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gtwwkmqjzf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtscxhlrid.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtsgyopcri.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtwmdvedbl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gtibuxnuss.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtzsruzvfh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gtokjehsgp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtrubsdirz.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gttaomhnuo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtnklwgzph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtnkvaizwe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gttjfnbdzj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtpukgdutc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtnjaieund.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtchqsctog.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtcrhpnpzr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtgggxiriz.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtbunmkurd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gtsbbkohyt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtowxhyicp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmeabkbtq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtqngnqhtu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gteihfuffr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtcevqrodh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtmumlwfsd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtizywhnnw.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtwlxljwup.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gtfylhmoza.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gtcqnxlrbx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtzdsgnjtg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtttkwkybv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gteilidxth.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gtkphzsgor.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkudqfyiu.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtkrvcbiiy.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtbkvvzgvp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtpfitirsj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtfvwoyrmr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtysgnvcym.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtlzbfftxw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtlbeomlzg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtvozslcmw.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtjgvuwpus.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtaaltnzxj.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtelpmgeda.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtdrrdcpxn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtsuffywdt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtfqjuceda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtkmzjtvzk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gthvdvdaty.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtmvvsechh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtczaazxwe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtuvviqdqh.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtlyjxisjw.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gtjredlwpa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtnjgkjgmz.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtrxkrhkin.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtaqstnvqw.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtrcgjjfod.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtebpdmwmz.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtapqdxogs.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtufeqcydb.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtxpnjuouk.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtssgexsmc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtsngktwmp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtmgqnwgnp.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtvhikotim.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtpqthadnr.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtwpslvdpb.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtsngbnhzz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtazgdkihn.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtqeowqvzh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtuuckmngw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gthqykrvvs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtifzfxuic.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtbwfkhxht.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtnlngqjno.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gthtdphsyj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtlkafubse.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtqfrlpjno.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtqgcgbwlc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtimliinzc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtapqbqpjc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtgclojifg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtsjmfsghp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcagrhpf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtwvemdyyt.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtpmhddriz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtovgparvr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtccdiojsx.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtmzyepjyo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gticvbeycn.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtreotlufn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtaoylkaiz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfupoubii.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtalgmolyz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtbczepemh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtqxmclenv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gttfcfdjcs.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtkeqhatlf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtjcazfpfz.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtvnobuuxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtpaltgwhp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtzpokkbpn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtihdaiuqs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtywjijomx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtkvbdvvxy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gtudiraeln.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtbhaogewk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtwelzuiel.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gturkerqiy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtkrxifgjr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtierulfeu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtjtrofzgx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtrpufgnmb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gttbqgskmb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtymyaxnnl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtnallmnkv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtxxqptzyo.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxznammxg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtzjhfrdzk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtsyzgsfry.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtozxhsdas.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtdulwydup.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtlqqhoiax.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtufuhcd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtwuyqefie.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtctsuwmuk.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtgzqcqfaq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gtfekopdfy.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusgyrqql.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtaubakhft.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtohzwoeuk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtprgmmnmv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gttqgmaovz.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnujllvim.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxadqdaiv.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtuffzfddm.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gthxqsezyw.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtmlutvghh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gthobrfohi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtoslqowrq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsqkinsr.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxpxzwbvc.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtaolsfpjt.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtddivpmnx.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtgnuggxri.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gttvawjzai.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtqthossdm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtpdtoduvs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtdwsmkgfn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gtrkvklzza.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtoyspsxbr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtnuvzapif.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtgrunbbrn.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtispvidgw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtmaunldog.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtighmnzbz.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtktnlwvxh.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtqytgfqsm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gthngslvit.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtegipjhhl.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzjtdypx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtmrxbdqit.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtrcpepnbw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gthzinyjln.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gturlvibzd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtnkgphohd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtuoeoxrpq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtdpeefdio.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtrterqchk.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvlkjbtpq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gteyitmrwa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtmkgwrzcv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtkzyqsroy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gtgqpalbpx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtyacrrysh.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbhrmzpzy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtiyveczvq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpfzvwdnr.html


<!-- 参考信息 -->