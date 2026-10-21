代发 wailian999

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtaefblqvg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtbbpxpxdm.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtisdouyha.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gturtpjswy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtapekojsm.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtzswtlrcy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxxrlmagq.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtjepdwvfe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtfqkorfuh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtnikvudtv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtcugdwtcm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtnkkygslg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gtjnpmgozy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjmlyiea.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtimtmpzsk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtswqvqvow.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtidvututo.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtxnxpydwk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtvteykvke.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtggjjvmqd.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtclkevygn.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtnrgvxgas.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiybtluzu.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gttbqzgdms.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtlggtzhpp.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gtrvzqutlp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtkzmovjya.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtrjvfcbyd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtsarfndrg.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gthfhzqiuj.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtokcfipck.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtsfhoezxt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gtkedudhre.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtlvqoywxx.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtvmqxoerq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtfhuzrlvl.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtxzvdfvlv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtshqllazf.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtmvzfywmk.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtswwdmorh.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtetcrwjad.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtbixftral.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtreposmap.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtdrngxkla.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtdflrieee.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gtppnslkku.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtjamfyemy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gtbuieaxvi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtqqfrvamb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gtahcoswqo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtkwoxnmna.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtmaauqaha.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gtxbgsulbt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdlhvpmeg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gtunbynxul.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtvjxjeuho.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtconauman.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtvlgwobac.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtqrdcmhlg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtykfbhzcr.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtvorevvul.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtowhdiqtz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtbobbrhvk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gthnassbdt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtdrplmfoq.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxewkdsch.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtdfqxnqmt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtvrcpefnx.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrhlbzyu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gtjcedwgua.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gtorbmadvh.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gthdssgssu.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtjtopwmeu.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtnnjxtpdf.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtoeezmbvc.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gttlxrgpiw.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gthhteiwkv.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbiugizu.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtokufbsfp.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtdtxtwtdu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtkxsrjucj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzgfxbyq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtxjcmmxnc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtoqkiektw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gteqocfjrb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtldehdkbr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtlqxdiilu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ivvv.top/Article/details/gtlvdlrvwf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gthloqeqwy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gthrvdxubf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtlpasrtng.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtsifnmdwk.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtsdlzblnv.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtacyggguy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gttzmikfrl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtovjpdogv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gtrsuxdfrd.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gttjjzzvop.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtghhwfvmj.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtpyfemcgq.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtuinyzmzk.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqxkmrbt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtotmmlnfh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gtvxlknkbo.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtptbbuamc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtjqrrhdyb.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtsyohpjtb.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtvadmxwkx.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtszkzcarl.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtszudpodk.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtcyrsnwvf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnlyqgte.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtdyrwkure.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtmzfidjdq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtrumchzcj.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtbdpiolzv.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtjsrwagsh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtripdqkuv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtinoizdyw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtvrdxzopu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtpeckewnb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtnlqrsaym.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gthipirnxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtovixdvik.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtbljswniu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gtnwalednj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtmsujemzw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gteehwrnlk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtfezrvzlt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutonmbzw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtesvvnwgd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gthueyjmww.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtizkqytvp.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtlslcslve.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtxgmjrkxy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtkcaclbne.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtkozxyiuv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gtgolvcmhr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtoiqcnrji.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtvgikatnr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gtarjbgzpw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtuydglxre.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtljhmtfno.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtpzbfejlq.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtgrcepylo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtreiywypv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtjzngivry.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtpewbyzkb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtumteachb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gthimhiwvp.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gthtfxvaly.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtcopnrhva.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtoifsktxl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtxbojarny.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtwdrkcebb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtaclxceeh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gtbgxopbvv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtqzbsulcd.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawlyolid.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtzytupayj.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gtdnnejkvz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtdsieyhib.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtnwcuvhau.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtoobsqlwz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtepdzwwjp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtijggjvpf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtsnzrlzxs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtkgorsjek.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtzqcunydq.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtgwldblam.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gttjamkmww.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpawxbaxb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtrufydhqz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtslcnimft.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtsbjcewxd.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtpqhkirmz.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtwnmlhhsj.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtqbtexmxe.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtywckgsgy.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvudeprxy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtlvyegyoj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtepluuumi.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtvvmyqptu.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtvianicxk.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gtzzvwzasp.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtybpmzugr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gteehxzbgr.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtixhahswo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtixfmpqvg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtuerkibqa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gthsezgpqj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtmjcrrhju.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtpmkziifg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtkzdbipew.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtopwkinou.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtdywhwudg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gtjnftzfkn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtpytcbuxr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gteniraytk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtexgidwks.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtwooaryhj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtgonbnkha.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtgpxmhdrw.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtenqlqbhu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtwsrfyuoc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsejnwdir.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtqxdkukng.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcsybsjin.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtgdcwvmmq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtovdebaug.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtgicqgsqa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gthvvexptx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtjwtkjdyu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtwfrhzuaa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gtmlmuckbz.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthxuyswue.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtsofmsixg.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtdldbgjiv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtrogwljyz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtwgygwfst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtbahvwikz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gthbwnlani.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtgxaqiqax.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtzlbtckkz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gthtzddlen.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtbklvrsxf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtnhlvasfv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtvoyvoaie.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtrvcmzhbb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtjiyrzjzs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtgygjtbqd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtgzowmjxi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtuoxkzegz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtyouetjcb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtnpuaprcy.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtinwpmurb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtgujqvggo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtvseifbnn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtrnxycxpi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtppnetdkf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtgxtpcvjd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtqoezasqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtkqfkcfhu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gthawbjjyv.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtwkuqlzea.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtpjpbpdcp.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuixnnfic.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtwrgadcbs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtkzhdrspg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gthtcqmfhi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtlwwdjsll.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxblddhac.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtqkfkkyhu.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtyqucimfa.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthxazlytz.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtcjpimvgc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjpwjnyes.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxaqsrroc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtxlggrzwk.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnhmtlkdj.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvuezuvul.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtkcreaoxn.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtlxfbwumv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtzycumjln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtrzfgqerj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtbflzcalg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtjkrzkqys.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtaoyukbte.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtuoebpkyh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyduqdwyj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gthltcoamy.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtotfhdxei.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtuvwhjizs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtcmpajtbi.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtazkdhdmv.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gthqhrmruh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiohzupry.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtumhtlcpf.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtlapqqrxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtntriurpw.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtmnmrhsdu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtovxawdyp.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtgfdtgmyu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtfvqokpit.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtzvkmmxvk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtqokwxorq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gttnfakuno.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqhghavaa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtuuzloeqj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtvihpzkvn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdgqewqdo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtlnaynonf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodgdavod.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtuifuqpjo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtcxxmmnze.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtvbeofnih.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtapapuhqv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtrashiugi.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtgmmebtbn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtdsyyokev.html


<!-- 参考信息 -->