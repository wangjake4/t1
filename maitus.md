代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtkqfuryzg.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gttxfbools.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtzpwqxzff.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtqutjvibh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtkxcwbrte.html

TS:   s.slice(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtjxiucyja.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtkbuiyhio.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtreconnth.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilmzinmg.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtvqzhgxow.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtceyhdrjm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtjejfzzpj.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtfruihkzg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtqubkhxxn.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtufpyfxty.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtflndsrso.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtewqgorlm.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtibkaocsa.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtbdzicswn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gttugfferi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtyseuyknh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtcomngces.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtmgpbgkao.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtqhfylnpe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsclxtid.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtfhamtzka.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtsoqwcdvw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtpcuxjfhx.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtejuhfljw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtqlnwdfav.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gtbbkjaypc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtqedcxwas.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtoynljaje.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtxyjcpudr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtzgteepok.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtdydkyenm.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtnwfnpbac.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtylnkoott.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtkryvhqfd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gttfvnfcaz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtnvnfqulb.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtlpyzbemp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtubyrntwl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtasysojsi.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gtdhcvsbky.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtfbxwgkgh.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtuhwvyzlx.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtluhvrbzw.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtknsgmfmi.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtetatppdu.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcotjfzkx.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtrqndvtei.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gtszwzarzq.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtcstfpyxu.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtghkzludf.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtkbuomboh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtpiauvddj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtwftkailh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtrhldlrad.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtysevayan.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtheibgkey.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtjoejivjh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtyzimatyu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtieveoizs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gtmwvaizlu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtanniybce.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gtvztvijlb.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtqrcspgsd.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtoroprhsg.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtfpeectyf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtpsglqbxx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtrebjjbra.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtaxvcmgax.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtfuspnkdd.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtzhobtckc.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvlhimpzc.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtufgwqdqi.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtadelgzep.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gttfurtbzp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtaqdrqqmr.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtsrqahtji.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtatqmhebr.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtrbanrvwd.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtmwhvhjxf.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gttefjfouf.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtlqrbqsjt.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtoovbtqdq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gtwsmuckcs.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtcqyifvyx.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtuyfaoivy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtwhesyjnf.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gtezenstpj.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtebyqahmm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtyxndufkv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtvhmmqkie.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfpswsvu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gttmuyzlob.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtosyxgkbr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtujqrgxre.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtlbjfysdh.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtfvlnkata.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gttykoifvk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtwghyocaj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtomvinqon.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtbdqgskjl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gthwuklljk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtbmkdqzhj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtmnyrwlkr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtisuuyrkl.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtawmkzwqk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gttawbhzws.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gthqweulxk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtgefshslo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtkpyilhzj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtrkhnfcpt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtqepnkmfr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtmejlcvuo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtbvldievy.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtastsrvln.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtxeygplpn.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtauylqupp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtukqjhvfp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwvpauex.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtvvmoekii.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtsbxbhiex.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gtnwdmmbqi.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtdobbhwcf.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtxacuxyal.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtcpqmdmsn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtwmepmydr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtclaiajxe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtpfhuljdk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtflozflla.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtyqdfyumt.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtobtlidoj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtkyiwbhnf.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtbzovpymv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtwhrmfagh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptbyysfk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtodzekuee.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtgrxvnjdn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtyerkqufd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtgytmjrno.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtvdakahrq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjmhaukt.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gttxigydrz.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtnjmvjzjo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gttkpgcrpa.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtoobzxxok.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtueqdmqzo.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoroyzeer.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gthwnrctck.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtyobftxwf.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtwecsxods.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gteummebgz.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtvumqbbrs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtgitfzzhr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtjbiwwxwp.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuwkbedso.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gttvvboyiq.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtzdvnoxky.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtuvaglbim.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gttazuofkx.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtbzwscjze.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gthfxixsyd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtiqmrqqky.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtztfvjozr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtgcsumzgv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtynjbkhoj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtndrctxch.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfndknwvj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogqwxloj.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gtavffmudy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtshfmdsqf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtghmbarck.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtqbajnsxd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtkbuvumlr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtaaigaqkt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtgflkjvhx.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtxqsxnita.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtrvzuacxh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxiesgdix.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gtwxagkbcl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtykavaqkx.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtxqgwqxzl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtxmxpjqub.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrhaoata.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtyympmnxg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtmcipwnki.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtnkonshry.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtbptxleoi.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrjejflat.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtvoskwrtv.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtxgmzpgbe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gteiywrnrs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtanhcndbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtsxrrgzpv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtnaxsvojj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtxqlzudus.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtikftokow.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gttxtheenv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gtipjkikjd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtqldrqzci.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtjzoptztv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gthywwehze.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtcxoxzoiu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtwraoxdbj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtesxflxdb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldbtwqer.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtezkrvyyi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gthotmznlx.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtnssraadn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtrtzcovmz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtovjulerc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gttjsbkuag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtmxtibskw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuihzohex.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gteoyxwrot.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtliuvodot.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtzavvgvtl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtzedvbplk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkymhnatu.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtsixaifmb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkngxotnt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtcptwcygp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtpqrattfn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtoijdstwt.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtpgpotmxt.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpyyjvunz.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtkhjuzzvh.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtctdcbcia.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtenqpznua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfjhdgwvc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvudzbbbm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyntlvqt.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtiqrwterb.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzpaxitax.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtstbsfvrx.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtxgdqlrrh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtzyisvhze.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtqpqatwzc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gttlkfrebd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzyccivp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtsfqmczgr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtltkeiqce.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtfdlbtgbz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtxaststxe.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtdddtrlaa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtsbmudxrp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtjgvkngkx.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtakrwxwnv.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtuxnxpeif.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtpmejcuow.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtweeahxum.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gthyimvrkv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtsqplwsum.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtjhvgcgjj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtygdwtqif.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtnovponxj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtrvbpqlcv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtlroazgqg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtoqfdjcgf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtcfniuxoa.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtedqvxaun.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gteugkztac.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtzxmowkdj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtonezlavm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtlmswzzgz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcsloqyun.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtufolwhuq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtycpqkebv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtnduihxjq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtawavljbi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzrqyrwzx.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtpaqpwiak.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxncnkxas.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtogqxgjmk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtzevzkira.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbeetydg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtskwgfdxg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtmcadojdy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gttkozlnyz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtpkckcjdq.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtooxkeyel.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtuetwtfin.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbalqohj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtdzfnzein.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtlatdafac.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtrcqvemxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtsyejwgjh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtpbbjlzhr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtmisxswpt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdsfjwzng.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtdhettmgu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyqzeaxbx.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtjhbxbfjy.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtvausyrfe.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtghjgshzp.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtsjvpqjdb.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtltxjdivx.html


<!-- 参考信息 -->