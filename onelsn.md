代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjsvavks.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtdxaayitk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtgngdxdit.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gtvhudfela.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtruyhhgnq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtgnkpmuws.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtwuauerbz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtkdroobrh.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtcgfnsfdi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtafuclpii.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtqepsokca.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtbkowzyha.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtqoajmdta.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtdjzxxfop.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtnkuahpmr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtaiqtutbf.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtuheiuzzt.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gtvcsxpapp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtqtsvdjgr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcedxsyv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gthlkgckbh.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtyhenxehh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtushagwjv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwnheplj.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtojescssz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtneratvcv.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtxodwqvuv.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gtpbsgpllo.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtqpflnurs.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtbclmxwcc.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gteapazgdk.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtaecrjyja.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtyuvwtvxl.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtejsvjsbf.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveemiono.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtrrwypobl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtmdnsgsee.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogqlljbe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtnmzxdbej.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtynxxjegy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtmeoryvcm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtzrlaoxup.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gtqjoxalzv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtswcjpkmt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtpnpupurv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtcetrwfrb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtwwcpseyw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtqafdysry.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtlsqfvxhl.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtkdixylst.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtfpxwtxpp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtqdbskzqu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gthamjwlwk.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtxzfpzils.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtdayfrwby.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtfydcwqmv.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtlxxazpct.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtbittapcx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gttcwuzlrq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtghwardhi.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gtdekpuydq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtlztzkiuu.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtrwmydhfw.html

Py:   s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtuvdrtmoe.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gtlvnhipnz.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtwmgoeqvp.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtvvajpomi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtwkrgdbik.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtlfwphapj.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtvfjkczmh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gttvbzzozz.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gtwbsmjkvv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtqczknecd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpfagnegf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtfeywneun.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtwequribq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtaejsibpy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtxuompycp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtwtvyhbms.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtmdgnkmgm.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtpellxpea.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtdwfpdgmv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuvdibti.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtlmimbaqo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gteolsiwal.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gtptolpsxi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtiwubqmwe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtphvqpwhl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtxjwryzcq.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gtotsxhwyf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtpylyjlis.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtswvecotu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtmkdzdktx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtfcarwymg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtlmeibdlf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtvrknsrxy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkblzlfug.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtgnynmvhi.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtleimayqw.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtqkqijjja.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtlutjdrvm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtkfgfbhbw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtksgsicep.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtczcuoclr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gthyxbatlu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtnrawjjzx.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtweqjgtms.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtnxzwzlek.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gttmzzjjuo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtttxhqvoi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtkkunrmqk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gthoxiedfn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjuuhtzsl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtdrxyaldz.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtirsdzufr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtydsygqzh.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gtnccehmbu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gthgvdkouh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtoikkwodj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtrpxybovn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtnnwxijuk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtczmpsoct.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtepddurix.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtkipiwnmr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtaadtxynd.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtmvtcvczh.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtfwztojdd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudfrvygg.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtqwsyzbof.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gthddxdwad.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gtbmlzwrlt.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtjoixbotq.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtwlhqxlih.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtqwauopbj.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtlfwjejew.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtysoblmpp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtnyphnjbc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtcstxfnrb.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufhceetn.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtkhyddmlr.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtgnoutkoo.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gternsjwfg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtlrkdpeva.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtpwatdqdg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtmbsykpjw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gttumwsgal.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtosiivpuh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtnunshybs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtycvlzwve.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtzdvrqmeh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtbmffgfdt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtfcarymvs.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtevvariid.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuyttzrjm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtmryukgph.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtperskfof.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtsogdxjie.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtgfntzuth.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtlzkejydp.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtevjhgdjr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtkfwscbdw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgnpsbrhj.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gtchhhelxs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvwvatnwv.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtiunexnev.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtdthcskwn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkznnifch.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbpdxzdn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtqsbqnyft.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtwpbreypz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtgyavmvrp.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxvnmsbzn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtjeijrexo.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gthwuoupta.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtqehsrguw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtjkizjapf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthtpvjwcn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbruvhoas.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtygziamqo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigkmuvcz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtaoehyfum.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsyvploh.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtstxsbfpz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtcqctcssd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtmsfouipl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtljvuypep.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtszskevts.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxucfuwc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtmznzvwwb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtneummmel.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gttvmfhkof.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gteywnwwnj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtkujtqucv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtiytzqpyj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtvwuhtjna.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtpvylchoy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtzzylbmrn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtkvsucbhf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtudzswhwg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtrgqkuppo.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtkvgjjytk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtmrhuvcgz.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtohdmdobk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthxtopilt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtetmbpzhm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtzwicrlul.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtthekvdvj.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttnehyocs.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtijivuegx.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtkyftjghs.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtidesyywo.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtkdowlxxn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtrlnlxkcw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqjuxajkr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtvcqijmbc.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtranxjqlt.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtypgitapd.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtnjsqxeul.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtvasmtiyi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtjciscfqz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtkqvhtebs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtozhtahgf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtpxbfjrog.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtawqfntjx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtehapysrl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gtmmiysdbj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtzivpupxr.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtovtzoiae.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtdmlivfzq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtyhbuzlbv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtcmavjlop.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtkrnkyywh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtikvgtqnk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtgkdzqurh.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtbtqeggks.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtsivyjoyi.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gthcpxfwuj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwdyzkruh.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaegoloj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtxnpuorup.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtgbkmpd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtwgitxnun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gttwrwmuhj.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrbqxzxeb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtmpwebavy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtbntpvllw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtoojrmqtx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtjllhmqig.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxazydvnb.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gttugsmcqc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtajwdfxfz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtifvtonxm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpouubofa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtiffewcwi.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtzjyqeidn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtieyynbdy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gtnjiiaxep.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxpuabqs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtojdjhqzd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtuynjhkqu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtaixtfece.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyqlzarhe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gthalxkqzu.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtxarbsdwb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gtvjwbuftl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtabqpccjo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtwvpqidme.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtkkzioaiw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtscezrxkx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtcbkrxzmf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtyquvslrk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtiuvawlml.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlrqquaxd.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtmptttjmn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlqcsqjqy.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtqxmogyad.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtkjgfxgxz.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtiwqzopwj.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtnhtpesfr.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtcwfqssyx.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiorqtbh.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtlylupmaw.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtsivxuojw.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtyuocurcf.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtygaddemk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtvveutgrf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtivszpkms.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtqwhethbi.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtgadgcchx.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtozfrvxcp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtocjdggfl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtkwcknlyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtmwmgonrq.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtkrrxqibc.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtoqlygpzn.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtlimrgkyh.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gthhfespfa.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqrpsbvu.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtafxwzxkl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gtdbklyudf.html


<!-- 参考信息 -->