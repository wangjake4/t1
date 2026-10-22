代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtpbthantd.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtskyjyrji.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtyshzrwff.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtbtevzb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gtaajrzhod.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtfffkjltw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtfmkzvdnw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtfgmzdnnm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclciapux.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtvtvykqed.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzphpmbd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gttwvvknob.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gtspizslxf.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gtepxzvimv.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gtzmxxoepb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtabzcfnco.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtrxlptacx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtcayixwoe.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtvkzugftx.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtxtqeekiq.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gtxraeagqo.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtmefphnhi.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtntcazyfe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtnnjjuemi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtjkmaywor.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtkmhnaezt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtdyfkxzzs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtmvrqdlkr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtcvjycvsr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gtgsjukjjm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtqzkgzbfi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtjarznyvd.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtakkrukns.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtyuqhsrhk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtfxolqkru.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtwbeatxds.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtflwlrqxj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtoiuboqhd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtgfgbluby.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtzvrqwiat.html

C#:   s.Replace("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtocrbwpsb.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtcbokuppu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtmmnknvpa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtigqonjyl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gthibfvtvr.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtrefvpjxm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtnppxfgbk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtqylaheod.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gtscoxfuua.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gtegujuwnl.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtzqucbhao.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gthbzooxha.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtbyqohmns.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtwxmhvdbi.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtonuayiwu.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtxqyccrnp.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtgememazr.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwqwjwpk.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtgvxhevfn.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtuwziclnj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtmplpgmav.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuishmof.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtebgdvnte.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtcfprszrm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtekkhmhfh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtjtwrydtw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtncuwchwd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtfadyjqou.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtxvneilck.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtmpvzldsa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gthqjnzwjj.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtfuorhcdx.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtfiidsxyn.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtfdtkikgy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtrkfgswik.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtvsstdfwy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtetjlnliy.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtskoboojd.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtdvpazbjl.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtoyowajwp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfiwnaby.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtnoxigliz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtcpdllwap.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtghbaukmk.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtwcjtvlup.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmrmvpif.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtgxeivkws.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtgnjsspax.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtqlcjttde.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtszjoqrqe.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtlalzjcfl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtaqwllqgm.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtbtsmcmyw.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtpsjacdss.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtnfljrfke.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtqnukdboe.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtqhpqegfr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtlvdtcplj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtctarmfff.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtdbyuaxpo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtzrqtrqom.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gttmyhkzxo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtyiifkcif.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtuaournck.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtmnzonolb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtlxsxjmlm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtrdipbdzl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtaaxftwlp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlkxfvkn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtrxyanjxb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gtlwfulrhw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtkcldtzdf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtgwylnohf.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtzvshwhit.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gtkrqriumg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtdnpqbcvu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gthmufnamw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxjelybp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtcnyrtdal.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtbbxokdzc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtzxpuiyfk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtncnuffur.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtoknwkhek.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gteimebwpo.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtumpscrmc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkzijwka.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtunqwhafc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtyirgxsnz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtfbzucziq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtlnlxgcex.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtcmvdcqpy.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtlczojrtt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gttydlpbkf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtxvrxewfs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtxosbfayh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtsgzqsbwz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtsqkjyqne.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtkkcerqlv.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtvnpaskxn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gttrufcieo.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtdkxtadie.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtholqodcd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtdvgetmhz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtfioydayq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtnxfqwsgb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkygrniyz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtaqoubzhv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtmlzlezdf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtptyxayuj.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtogkqylzg.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtgehepqjj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gthnxvarht.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtbbuzefzj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gthtdtetdf.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtypgquadr.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtvnxabiad.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgdttafy.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtzrzoshwu.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gtccfzolmi.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtpxjmwfmk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtimvxxg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtnsawajpl.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtiihdojei.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtighcerzo.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtrcdkuhos.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtfennolte.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtbgnietls.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtyyhvwgyw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtobehwfkj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtdxtarohc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtrllrckdy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtzxogypri.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtuafdirwq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtzhsayytb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtemhyjjbs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtwlsjtbna.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtntjdrqhj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtsszmtpkn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtnftxvefe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtbdjhxnen.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtywinnezt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtemldsevz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gttqijtlpk.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtsngwdwkr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtdvvehpzy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvkyzyugj.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtmkrqbytm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtknbauzgy.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gthtsufhyb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtkcviqtdf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtktzblukh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtdovyjivh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtjudvtepq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtvpviewqd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtznosvtog.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmmbaqkfd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtvfpbxggf.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtaqjhbuzr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtplyxjckd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gthmzmaebu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtdyypcimo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtqwitcnue.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtniwxzqea.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtynjyatud.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtsjzmgtdu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gtiozckxdc.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtnyxvihvh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtxytegond.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtmcowqhes.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtfghrgvdo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtwuvcgldj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gttlyugbrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gtygvvcepd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydfhwhvu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtqscrvmsp.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gtvalammkv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gthhbahmvx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtcvluweca.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtrrzvzqlc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtkgfzvrri.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtxkcuurhv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtuogmqzav.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtopbtjdyg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtgcdgveht.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtsrzkaezq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtgtjwcxfi.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtautudbft.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttdzxengn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtejtjabqh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtygcpdcsy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gtlknhmbxy.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgrjecdpa.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsmqmqkwz.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtyfvovumy.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtainzqsof.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtzlewiscg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqowztuhy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnnveqasu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtpbwglpat.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtawlyecsz.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzhfytavx.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtaplqxhzz.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gtflzrodvr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfrjltua.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtwqqgjmhq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtkndhsikt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtxlklzdij.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtkpjlsdcg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtocdbdgmn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtktqvkear.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtansgqavz.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtrivjwmle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtziathucw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtzrunrihy.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtmpeimnwo.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtqvelrdud.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocndixht.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gteqbnmbxe.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtxlabeckg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtmjhndrtz.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtxrfgddsp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvftdljzu.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtydwfhuun.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gttfrtykim.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gthjkmpmug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtzfruvdly.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtppcxfvmb.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzcadwvzt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gteketdqxr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gtkixfwbzj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrufhmjbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtqbcflsdc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtemzeyewb.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtfytuafry.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtsfiwshcq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqzjcyar.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmabsyeut.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpzqhqvnk.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtvyjikwcl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtmnldzqln.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gteapeoxnk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtywyxohuz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtorllskym.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtytstfwev.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtpqscxolz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvrcsbfok.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gttbkkabcn.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gthqydztmw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtjtcwufbs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtslxyfdmu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtuzooawma.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtvjjqzchr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtewztzqao.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtjnakfbad.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtojnshtqj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtlgqiiyym.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtguftkkoa.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtaozvwywi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrybdykhc.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtibukpnjh.html


<!-- 参考信息 -->