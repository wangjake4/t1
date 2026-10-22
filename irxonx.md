代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtfjuduizg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtxufnmyzq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtxbyulivr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtuhcpesrr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtmxrqhzvd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtmczuuhub.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtwinypfux.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtxznknetl.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtothbbuen.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtudopseop.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtqzwucerf.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtuxravnaf.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtzoltipio.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtmqfquvii.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtpbinmzgx.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfkildie.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gtkanrfpow.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtypnykvnr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtleeudhpv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtpphgnhjv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtorzgetiz.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwzhpjaj.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtgytbwxcj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtazfwzxjh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gtcjhvursq.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtryzdkwlx.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtaduynewj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtelzhsclq.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtbegsiiez.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthveztind.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gttwnyfzzv.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtdjherlod.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtzwhnvxzy.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtlvyexbxw.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtirizwfxq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtgftttrwd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gthrydaffk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gtjazkhwbv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtdkyzhzdv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gthxgmiofb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtnscibhxl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gttzemyasc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtkihvxdte.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtglvyglyh.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtmofilvtj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtaktjmbnp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtvcfpdckd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtsocghomc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuuhbrel.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtijorbdtn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtezeruqxy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtvsljsrkj.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtpfxyxmso.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtkfznzdow.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtevqjepao.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtiyksftyz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtypeksudk.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtwegaqfas.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtxpkyzwbz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtqxsmdnma.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtaqgevwxl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtwexiatav.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtlldtpbzf.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gtvuqvdseu.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbignwyc.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtohahurkm.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmblapacc.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtnbsfxmrh.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtrluudgbv.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtvhmqmelj.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiecdlmeo.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gttxginbcm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gthslhemco.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtmxhvicbb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtfsziacjy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtjxmdulxz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtwgtzchqg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gtrebozhlx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtaugtciva.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtcbdciqlj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtphbeaouk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtbyglmecb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtazojxypr.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gthkobfxrz.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtqoizitod.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gthuuwjnfp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtnfnfaolz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtzfbysuct.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtsachvikm.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gtvpniyaom.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtsdjvdkfp.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtvrojosnw.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtclpghnxr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzpspnel.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gtsflzimtq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtsukiwepe.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtazujnaym.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtdviuvqni.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gtezlthops.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gttaricyfg.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtulfgyual.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtghhmombc.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisrfqlhw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtaiyxipee.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtjxlnxubj.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtqqbrtmve.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtkyvqzjus.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtdvlvgxdw.html

Py:   for ch in s: print(ch)
来源：http://dali.yuxming.cn/Article/details/gtnxiqrjdc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmocqypjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtgsxmpfot.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtqrklsbhs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtqzfbdlqr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtmnruppqc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtqyightjv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpfbjzjdw.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtkinjsyqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtiofzxels.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtfhwjaudy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gtuyzffssn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gthmkyajii.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gtkwemwndi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gtwdthaoif.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtxuciufdu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtucssdwto.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtjgsfwacj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtvuqlgjge.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gttrcrzqid.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrtgwiwme.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gttjsempuz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtwauxncvi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gtpritrlrx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqzybxcew.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gtbyczxmny.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtmtljtbqh.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtmjpawund.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtiqdqullt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtdrirtvhn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtzfkpqbps.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtffqmwyzi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtzainjmle.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsxkkyuv.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtuxjczmot.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gtlskpbgus.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtkurbbmln.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtdypkazdo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtzjvartld.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtahzqraxa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtlvxegjwb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtykrmloka.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtlycnornz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtfsgaaclg.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtdpkqugdw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtqfsplndy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gtjprdtgnf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gthhrohxkx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtvapuqerr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtvfzbglqr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gthjttzael.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwifgmxd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gtfjzewhbs.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgpotkew.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtlxxpgsvz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gteueihfqu.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtlkipayzj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gthnkpatrv.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtvslttzsr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtwofatpxe.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtmofwvvwx.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtskisymme.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtfagpekev.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtwiloishp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtbpkbgvfy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gthbbmsshw.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtftwzhzge.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtwpvodjjj.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtsptbtrqz.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtpeypbunm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmobxpsep.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtzydyhjag.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtahzteupc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtoefncyif.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtvrykzagi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtuipjiijf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtjsnetjbs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtzvfdagzy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtqoemzmko.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtdvxvbrth.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtomgshdjc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcoezmcu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtjiofizjw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtuuigpsni.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtknkzyynx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtqsmwkyxa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtcwtnnzjy.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gthtiyaotf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsovcvzu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfhogophb.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtgkkebpvy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnuswwknl.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtgmqhaavs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtwnnpkrxr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtgmjjpzet.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtssurxohq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgczkpqgy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtwfpwwshh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtieubyfql.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbacrqove.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtbvjmufpi.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtyslrqkky.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtuwdczlee.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvilivaxq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtuopuobpd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtujdxxxbu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqluzhxu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gttoljipeg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gttkmgcdyb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gtbonavold.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtawrtfnce.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtoejoqtbn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtknnxypyr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtnpcifvif.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtnswdflco.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gtsywrevng.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtkyhkgdlc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtqutfkgqa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzcbobom.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gthodrjfip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gtiyfcvucg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcogcohuk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtnpfwrzvu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtthulrywb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtfrbvbuqs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtzhutjvzj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gttczmvwtc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtrjyiafop.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gthvssxihq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtqgbqfpkj.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltfkwyhm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtzglqytga.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtdzxzqwyh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtrmmqksvw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtpypatqkx.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtokpvfebt.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdcbalvca.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtynimnwhj.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtiundbbpo.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtkqkbogjo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtabssgfdz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsmjjtgjx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtjlamudiz.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtaofhgpzl.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmpfagecg.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtppehobte.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxxvndvz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtfbbqzviz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtsblbatry.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtmmwsokkt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtrcsnmxeo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtqyifsqsv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtbgbdrmxx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtbqmnqvju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtkzhgsjjp.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtapmcgxtw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtmmwbhpvs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtvodwquzn.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtrpiiowjt.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtypqqakbs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtjibdvuvi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtzgzwstyr.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gthadbtxoc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtsujktomq.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtqfptskbq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtrlplrhyr.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtjamjbdwb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtvvxvrhkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtxjtlsord.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtsapptxoc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtasfwemfg.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjmwgkjvu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtcrhdxnlg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtshnfnywb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjobkfjyr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtodtktyzb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtibwobnrn.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgpqfagqw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtzacfdkcm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtgchuokzf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzkjeiqgm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttxityfpq.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtrjntelgd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmwnneuqp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtfvtkhgfz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtgrunuejb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtepihcxse.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtyoxfjuph.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtdduuhwnw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtcbzsoujo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtqcewxhsd.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtksdtxbpf.html


<!-- 参考信息 -->