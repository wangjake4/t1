代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtwczzylaq.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtfpaucwzp.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtntlmmsik.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtpnnplgly.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj202588.top/Article/details/gtyzjglmma.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtbfxelfyf.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gttjkdtwwt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtilvwtqyv.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtyyxhscrf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gtxtxinkpd.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gturefeufj.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtizuovokc.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gtrocgwftk.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtoyvjomty.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtvkvpzeqr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtaeltjwtl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gttecjbqja.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtkrgngbdv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtpgouezim.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gthesyejoc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtkncampgt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlznxszrc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gtuwdlaaji.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtuwsadura.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqmnecev.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gthuactzjn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtadanqhxf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtcicddbjz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtwzzczomz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gthgwyoqbe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtolojaxth.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtuuudowrv.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtmrnpfffp.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtaahbzwsp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtnncgftdc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtivcaoavz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gtseabcxur.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gtttcdibkj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gtodfijvlf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxmisppa.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gttvjqvkwx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gturovkjsk.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtaitzyqhn.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gtpzzgudzs.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtlqrspyof.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gttqhcwkvt.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtspzptrou.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtjypggzla.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtrutfwwnz.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtbgraplvy.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtnnhnlwmq.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtggaiqcgq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gtgxnfxxte.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gthyjpwdav.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtuhuvqbgy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtbiuhbsfk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtkqjrklca.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtmimhluzp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtdpcwnawk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gtvsnfbbea.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtmlkrjgsz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gttlavhffy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gtnspphjhx.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtfuvoklrp.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtdtlizlao.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtjpivbczw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtgzqvwhdn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtyymypyvj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtcxbwvicy.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtcizwuxqp.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtonumecwk.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtivmxhapy.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtdgokpbxm.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtdcjmbiev.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtflnhaotv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtgmihwrgq.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtodciuabl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtjxyvslsq.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gtlfxnbked.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gtopdnidml.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gtqfooyjiz.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtijugejex.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtsvezjfmv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtrvbkyqbx.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtrbuvxwza.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtoqylrbyv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtkcpyohwc.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtknbscpde.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gtzymxsrxy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtexbanbyz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtxostfyyz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtcpwpdslh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtfsgqztkh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtuauqizbt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtqbhoaeum.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtomyhjidd.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtmodvdqba.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtxvkrczit.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gtltewmnzi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gtgssmrvji.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtxkiiqhpa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gthtxvdupl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtwkymqfos.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtprfttgis.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gttlgrveyk.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtjismntcz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtmsxirthh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtldizdkkz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtgqohtwyu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gtearmsdim.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtivvhwrqb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgqpdnqie.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtgombzbzm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtzolwgclp.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtmmtjuuwd.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtvirxhqyj.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtkfclufmh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gttqxjsgqq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtncwyizfs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtfzjforhb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtdxhmbudy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtygtfefok.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtdhmpxrdk.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtyoyyfcwn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtyjkhylwd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtlkxpgjro.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtqfdfeynl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtmsvwtkwu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtxgyxgwht.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gtownhzjpq.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gthtpnrfpk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gttuvuqouv.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gtlkaavhjx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtwswjobrv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gtibtcqwpb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtctuetcpd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtncqwnnay.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtutabcxcj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtfdsdoylo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtzwkomscn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtujwsxpla.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtacrwvpdj.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gteykjltty.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtrgaqhbjw.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gticecwbtt.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtzdechbvs.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtcvcezpee.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtzonkvtop.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtdtdsdtke.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gtohhyrmxe.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtkmryxglw.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtzoutigjn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmreuuodv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlrkhotnq.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gtlrykxbzj.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtevrdlhsq.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtrkdbkjgb.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtczwsrvkh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynzjnpyk.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtztitvgbl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtgxuavxpk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtvamjkhav.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtznqnrzbq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gthdbtnejg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtmzbxlvsc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtiarskfmo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtqhuusolm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtsngpfzjh.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtfcvinuei.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtsljdkmhs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtttoryidb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtpdfghami.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtbylefouo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtuolpbhcf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtjdyfnslf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtmnnqooku.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtupreuluh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdsseeobk.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gtbqsttsys.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfsyloui.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtwxyyxksq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gtjifgbiqb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxibtqvj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtvcndwjcx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtoytndbwe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtjxbpmbqf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtlrlnwbup.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjvycefam.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioafwhwx.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtearocqgy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtlekxdgig.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtchevfqxl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtpdwfybsp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtvwfleluh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtgpegjemk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gtzylgmxts.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtsizwtjgv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtvaumgytg.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gtdjngrqbq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtisxzohhe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtfogdjhml.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtdbwgjrsg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtyalrflbt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gttizpleib.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtqpesifcj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gtxdtlnjga.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gttesntymj.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtixafsatk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtxfwmjcuu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjgneoaz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtmzeurymx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtejeadsqr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtewkbtocp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtxpxwsilc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gtqaugiaqe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtemwsebbg.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtbezvobvo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtlfzhbwzq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriwlckeu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtzwzivzng.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtolcxppfr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtiimnqobx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gtejpobama.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkwbqzfiw.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqrhqgfxn.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtaqwyvwac.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtlmxrjogh.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtgjdkiacj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gthbffjvnr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtiiusumlb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtiesezihx.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtliujohal.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnbmunbvc.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtnxcdgamr.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gthtvkbgtm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtwrhgisih.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gthjayytke.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtwatmtyri.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtgbtufwxv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtgzpqvcoy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtwljbbgcr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtvwclabji.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtdxavmzmi.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsthmhwhn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gteemqmttp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtvgbsfkoc.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyqazhpo.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtxcgyrnrb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtyhpyygry.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtytknnksx.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtrflmxvka.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtkfaepzjy.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gtxbcdaihx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtetvdkppg.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtjpmnmlgl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtvsyuvtlm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtxgvopvgf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtkansvqcl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gthgucweri.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwpebugsp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gttoalsvwy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtdofcwvgp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtmgnmsjnd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtqgsjvqjd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtwquqodvx.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzyizastv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtrcsmkkhq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gteyyhaizm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuvxpftzz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrenskqob.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gteivgbxjd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbnfllpsz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtgnjaunkp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzcutiqqg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtvrifxnbl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtkpgoeheo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtwxligysr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrlkaqfz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtkwlfxycb.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtbgkhasnj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtyheufdzp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gtzjevqldw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gttoxmaybc.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcanyjmv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtvejlmqri.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtsytogkig.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtttinxjwl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtxkuwkcxc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcbgntzkn.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtmbmpstao.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyklfugod.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtsxcuzgee.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtbxfgpjpw.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtzqhvvoxu.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcceuodul.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtldwxeuvc.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtftodydia.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtrticdbqd.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtsvlvigjw.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtlsveregy.html


<!-- 参考信息 -->