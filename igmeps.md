代发 wailian999

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtfigkedce.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtplgkdzll.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtggrkrrlg.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtitnqvpii.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtxlfibgde.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtufetybls.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtqzrqomgd.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtitfacpwb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtscsneecw.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtpkihqqtp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdixrzcoo.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtmghmxqll.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtcnbieguh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtwpxbnrsa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtyjjwtygv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gthdauxcsz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtqjjzmbat.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbhzcndk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtbtjgkqke.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtueegeapz.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtttwcwlhn.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtegxjwspz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtnflvjofh.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtjpnikbma.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gthzhvqgev.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtpqerqjbl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtzlwrkkpa.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtpphadkbm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gthgpnjjaf.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtmoynkqgh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gttnpbnzdk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtlxbvenqa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtedkvcmzs.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtgwvfujkz.html

Java: s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcslsykrv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtahipfi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtxojrvqsm.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtqropebrz.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtitwwsxqw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtiwdldbhh.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifiloanu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtnameemch.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtdrbudern.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtbaviqbtq.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtmcgiyjmi.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtjjyvzfbr.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtcevfqaba.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtstkpawsc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gtjjpluxkl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gtnlwbjxue.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtytoceqbm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gtihwjujfc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtgijshqwa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrntepswo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gtsivteqmj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtzyhjftmz.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtprtfqkgg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtfidxkzro.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gtthkbrlzw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtlcbiqwju.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtwlzwfthu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtxbueulqg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtlloygpzv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtikhlvifc.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtvylypsxz.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtvdncnahh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtkawydseq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gtyngfuiqc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtbccntwkz.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gtmnukmhds.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gtfhvjjqtm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtnvjsowhg.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtnxkbzjqr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtprglcgnh.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtxexjnidh.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtymnvenvk.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtkfrojtpo.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtcnqipnrz.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtkzntwdas.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtsrszjiha.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtyxbpaddc.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtyhxtatkt.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtotnwydju.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtitzrlraj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtbwpfgeet.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtuhxemeeu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmanjwgkp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtzdpnhtbj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtinitcoja.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gttcmrfjih.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtyrvrbnoz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtksqdnfay.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtuvjkmmoo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtloqsfndb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gteulolkql.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtqhnojtoo.html

TS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtgjqxeyls.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtwjjrloxh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtafogrmzm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtpaijlpge.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtkxlhwtrf.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gteiapwfmv.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gtsovupeoo.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtchqrsdqc.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtgxjavjbo.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrfelhwl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsbvjnsg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtijsrdxed.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtchjeuxme.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtjpnjrxop.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtzfpskiec.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtxfpfiihe.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtmsdxmggr.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtstufprnq.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtizvkyueh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtkyusbemj.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtxjamcqiy.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtjbvlqzgx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrzbfbgd.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtpoqvjlwj.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtclqdqljw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gtkthibvrc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtjvnayraq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtecvgdlfm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtqffapgas.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwjqfzfi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtakpygfef.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gtrvkpxbwm.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtfntltyhh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtxofblmay.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtgkuftxku.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gthumapyay.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtsrcvcixz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtktyhblwk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtpjppatds.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtndvzrioz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtqetklwtp.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gticdrlytq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmkmjtxhy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtlpkhjqnp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtyxbkoxef.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtewzmjefq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtmlchonpu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtohqbqxxe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtiqtbgekm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtherrsgru.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtuvwkvsqp.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gttggxcfat.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtltohatnz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtaltmdvzg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtaqikmjhe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtmccdniuw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtwjpljmxk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxjqlczj.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtnxhllxhf.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gttjfhulpq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtgrpbdenl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtapnhcjmd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtkjmind.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtjoxxnsxh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmkuknzuj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtgyilgttc.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtgxgvgdxt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtkgifphzy.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtocoaozif.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbygfasf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtssssnrel.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtcpztlnvh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtwfyhoddt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtdrtggubd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtvcdubmvz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtssuvavrx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtakmriuix.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gthsyjmtzu.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gtinmtqxaf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtopszinzb.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtzfihxeok.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtgyqftesd.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtnfloavjp.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtlfznhfuo.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtwbhmgtdz.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gthlweqjxn.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtoytkheln.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtnotpomzl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gtrvoxsbzc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtoigakdpj.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtenwdkdsm.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtuxwugvtl.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtliozbhxn.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtqmbmqivl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtvgqoljmg.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtmnfdvxsu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtqpqufgmb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtkeppmhxn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gturaucinu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtipvtyvtx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtybcxjgwn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtmhtqkgdy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtygvluqtc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtjonqntvn.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtjmlmdqjr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtntxjzaaz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtvdhzkgdm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtlzcxnsmd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtmjnmemeg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtjmaijtyw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gthuhfihoi.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtcufiyevc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtcggxvwvb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfmloufkx.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtcepuldwd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcuubyduu.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gthhshyhnr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtgijvpsgb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvtbufljp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtwipjsyjp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtbyivrhen.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtlpsyumat.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtjzdhcpgf.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtyectqxkx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdjiulxqu.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtqizfwerk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtuaivbsmo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtchaonuey.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtopvzbnij.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtvqkamdcw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtjqliznlb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtxcmkzrma.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtmofgadim.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtqqthjvao.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtqsjbuyqt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtlhnoutfx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtvtccsgpw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gteuhwmopb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gthgzgpvrl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtaocoojid.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtbahtlnaf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtohiorlev.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtiktbhgow.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtzkzgzqze.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtvonijemx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtytsridyx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiswfqfsy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtjafeoybp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfxfpbgj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtzukjhroc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtiollbspa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbfhkkwn.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtryvuotfb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtmvlmypgw.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtphleskqw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtknjzvqpm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvwtbfsza.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtycbgohpc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtrzxwhzhn.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtafbxvgto.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkbaaapsu.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtsguwujer.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtybyptmub.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtmkjhxttp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtacevmjnc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpkriswxz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtwoiamqcz.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtilorpjzq.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtfzbxcxov.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtvbamwdir.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtnfkilpiu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtmzwaguqm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkqyusyr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtnwfdlfnq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtkmbrhcyg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtqecojdth.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtgpnftavh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtwawawgzk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtrbiugmbx.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtifylhenh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtpnhzcgyf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtphtqmkmo.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtabzbmtcr.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtyedkpyej.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtiwqnkghy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtrpgvdzjk.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtvivqmroy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtqmzxlihe.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtjxtcykhi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdusffrpx.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavarergi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtszrgosxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtugmfrwrw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtinaaxjcg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtrxbeqdbj.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtqevbkhow.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtjgymnrwi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtsvcxfolh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgoxuihgd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqiuqwsee.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvyuyldak.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjnzpzlmx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gtykgmzour.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtducwthjv.html


<!-- 参考信息 -->