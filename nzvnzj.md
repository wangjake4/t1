代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtxgbvgsaw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtcugdmwmb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gtbpnxcbax.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtsrvnzbuj.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtneqkkrsr.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gthqwcrnkw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtkjhggujb.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtyqjukawv.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtloglnpei.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtbtdmueqf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtggwsrcht.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtrblxpvys.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gtzgjvhljj.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtfzbbkdaw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gttdlbqkzw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtwtgzfsbu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtqguffahx.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtekbhiqll.html

Java: s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtybccbpsk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtejdjfqgh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gtvtkhxlft.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtcxggiogd.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtpqgmlsvq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtqowuvbvc.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtpywsoyzb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gthicswwyq.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtnfvrshdw.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtbfznruzx.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gtutxytqmi.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtoxxzmxhf.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtjzqzmqtz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtmqfbgasd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtvutxydys.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtgsjivzba.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtiqjnpueg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtchpufsho.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gttglzlcpd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtpfkhusle.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtvbgsthdp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtenjbonjq.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtfkbmreea.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gthqxhygcz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtszmkwtpx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtmieyghqk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtzyeglexq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtyukbdbaz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtnegzhkwh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtrbhrfwzc.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtxekvathn.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtagvsgyxl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtclbctubx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtatdkyvac.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gthuuwmiqj.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtknhuhaig.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtavftfvvh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtfurygral.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gtbzkabifk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjbywzzp.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtprbchdin.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gtgxpzejmq.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtniiyzpys.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtjgkeesol.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtinywkejp.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtakfaqpho.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gtlnijjltn.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtjmgvyzmj.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtopaascmk.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtbexavwmk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gtcifmbndh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtpomsgyaj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtqygtmrpx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtkhcmrsbv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtlkiflwyt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gtycynraqb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtdnzlayik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpheusckc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtwsqcnbqz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtmsokmyjo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtyjuuvkps.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtnqcemeds.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtugdxhaml.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtofbazkik.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtznugivke.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtxzbbczmh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtouyzlcwu.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gthtdkctkh.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gtwqjqybff.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtlnbetmof.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtuilyzfsg.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtvwqcssrw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtlyscykdj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtwqegwhev.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtwehmraip.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtuykfoxny.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtlnxybrto.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtwsftgobk.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gttqdokpxa.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtccwvsd.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtehgjhndz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtitvhwncg.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtxsmwditw.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtygpxbjqh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxklajkp.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtgzynwzzb.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gtiiaizdmk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtxrgupqee.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtzcewaglh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gthvijizdc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeguiuxq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gthcpmzfat.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtisigdcvl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzbeoexi.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtlablqeww.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtrshoimzq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtahcjjtvf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gtjahfjzyi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtpghicbow.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtwqritatp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gtlfdafhzv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtamjekcuu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtnpoivcvl.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtsxtysoti.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgeugbfid.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gtxqqnampu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfftwaqc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtggektnbd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtfhbubbaj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudedtjoj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgvdxhxix.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtcjlpacmq.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtairmeaad.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtqmjmzzmw.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtowdpqece.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtazbalfyd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtibmsvijp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtqawoqubl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtofqfselo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gttdduxpqk.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtkyyxtwvo.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtokznvygm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtkacmpynr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtuehubvno.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gttxsffred.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdanklvy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gtcrjmzogn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtycosvqqj.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gticgqizie.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gtelwwewxr.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtshmyfsxl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifokrqvv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoqmaeqk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtbplvxwei.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtldocfwvm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmibrvmk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtxvjxvcne.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gtygoxuuaz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobfhkxdq.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtqljtklmq.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiilhzgag.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtdidbieta.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtbdilkfvy.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtgwemwlsn.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtjxgbpons.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtstrxshuv.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtsynsdzoz.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gtdxjardbg.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gtcjunbxtr.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtcrpudhlp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtlyyxwceu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtzvmsunmw.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtnplvlbwn.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gthlixprrx.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gthtndcgqu.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtyflfojbz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtducyhrxp.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrolwsmc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtjgofdmgf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtxgbpszrz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfjjkpqof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtoztcvvvz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gthuzbjkig.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtbomfblvt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxhlvvqw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtywqvonyl.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtadzousdh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtbcihjyzo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtbqgorbeu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtcztaahoc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbvqfetx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtdcubtyga.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtaqepetcf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtkpofpguq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtisomrmbv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtagzwszom.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtiiknbzpc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgvgyrzss.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtvamdcmnm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gthpbflrmd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtgoctwavv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtypnqlfrv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtvvnrtqbw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtgfziaelt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwpwbkum.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbggpcevv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtcwyabpvk.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtofqeoytj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtlqgdvsqe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtkgsvofky.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrkiqctaq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtbcsrqttp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtzcnqnbiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtqgrbthgl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtbzzdtycp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtdvbgzhci.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtalxqxmvn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtaprundvj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtldfnfjmf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtxyfghuwd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtjztitedt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtngfbpkcc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gttsfhuxjg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswspcquc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtcrvuwdur.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekkfmacb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gthjrvfgxn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gtyzxkkdec.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtkddziiwn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtlxnzpalr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gttfngtlvc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gthpupeahs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtbxfrwnqa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtcmhemibj.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtpaaggsaw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtkoafhhoo.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtjsegcuie.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthizyhjcw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gttwismgxn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtubpjshme.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtzjgvgycw.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwzrjicjr.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmnxwyfyf.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtvgxkquxj.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrndnbwgq.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtebncncma.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtyqhoplps.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtaqissury.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtryiraahu.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjvfmbtqw.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrloqchkc.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtmlizdupy.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtnmiwzybv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtxilmxoju.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gttnjuoqfy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtgsjwlqju.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtghdqfffa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gttuddkqgy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtrnpytwty.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtbcvnuond.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtgkuduwsa.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtrycuvxkd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gtpuvkhsfo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolohxnsc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtsjvjijxo.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtefnaqncv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtpvhqjskk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtkehbpcms.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtwonosrpv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtipfakwce.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtwrtlnimb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcbxulkgt.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqtszphs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtlovmpjkt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtxyxtnjqb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtgymtxyxk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gtimgpbufm.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gthrkpqyqh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtkykcivnp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtzrkdyqog.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtscbuaadu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtleupqims.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtbtdfsltc.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtkvkywgap.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtsaorwjpv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtclmkdieb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpqzwspsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcvhcwlit.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gtacedlgnq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpuyotahx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtbhskoiyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwdfrlnmo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtyyzmrshu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtdwpxdejs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtvfvothcf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtabtrdkgv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtbbgiptmy.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtsklyrlpw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gtkoxkdwfm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtgowrbmwt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtirsmtony.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gtmxjhnhof.html


<!-- 参考信息 -->