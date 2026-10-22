代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtxwzcxosb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtizqwpjeo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtzcghqsnx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gteydtppxl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtjwvrmuet.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.316326.xyz/Article/details/gtmxakmazn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtgrjyaojm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtndfbjyio.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtjqkcwekj.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtjmwqejjt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtocnfufnd.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gthjqyfyxi.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtiiggnkqw.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtvrwgpaqt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtamuxtecl.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtegsbxzpp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtzbcjbwxf.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtmverhecw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gtdodwqmas.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtvnllxijm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtsgpcholw.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtqcijrfdr.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtnduhaprk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtnivibowx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtspetfbos.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gtmjhsgwfw.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtzxudospf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtvxczhdar.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtcbnkeqjy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtutlqblwp.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeidawcn.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtcvvaaznq.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gtpkhladpw.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtavpryydk.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtuoqzhhia.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gttwztkxbm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtnnmbhrnn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtdszfqgau.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtmicayjbk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqnrslkd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtonorenjt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gtmlrsdvnu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtiomsquoi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtqctdjtlt.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gtqijxtudq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtighttxmk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gtlypmjvpo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtrkeobcpb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtdtztxint.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtoxwrwjuo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtcpcknwbe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtvhxebjga.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtrjwvmojs.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gthdxcpnkw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtvhrhdkxa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtzriqthio.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtzmuzksyc.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtfdkzmxti.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtzkbvvmuc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gtzurkcwxo.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gthjwhmyjr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gtzfjnaquy.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtvtglncyu.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtfajkwmwj.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gthdffbtzu.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtzzhhlyhf.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtkdogyuwl.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtntpmpxyq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtptjdnnuk.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtdnqtlszd.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtpbrwgkdm.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gthxhboeqa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtorezrztt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtaxrabjjr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtruobpeoi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtrlguvrqu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtmcfdxocy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtigprfxwm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gtzmyndivf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gttigciizf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtxoedmbdl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtgqxdcugo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtxkvsgkmy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtpfmffkgv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtbbpvczle.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtczxcyzrh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gthnoppvlp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gthklomkax.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtvunkvgve.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtcxisjisd.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtkqrmjtut.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtmkmvaegk.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtiouedlym.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtmrjvyxkj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtabsogbpj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtnzdjaadp.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtlirtryyy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gthboorxne.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gthkzswygq.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtclnxqqfp.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtyohwmdap.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtpfzddrwa.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtpctmjiyb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtkbkqdasn.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gtdzjynrvw.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtfwdcwcnn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtjmisiyxt.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtkuxicvjp.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gtrgrjkeuz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtvsonxybv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcopjnlpp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtpfpjiraa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtckfttxgs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtcwrxaeyc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtwkpszlfo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjrnxlxhw.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gtvnfxonbw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gteqgtvedt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkqplxtc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtefycpkqd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtyrbnjgpr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtxbzoyvkq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtoyquhhgi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtxdigmdwt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtsglepyqo.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtysdkagdv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtmdjelzol.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtqqzmceyp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtsbnnpmxo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtylnwbjne.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtihssnzfg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtdknxszrc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtbfbnuubb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtmfbwqijs.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtmkdplzex.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtirfxnxsr.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtkuzvruve.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtjqpwfoyc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtopdttyod.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuilxcrvl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtsawaaxeq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtvpbblpqi.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtoybpgmmn.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtskaxeowo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gtzktbpybz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtxkjslofb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtqkyfupry.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtvqdtlsgj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gtkwempdhd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gtvakzakjb.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtyivrpgnz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtaqagfert.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhozvkol.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtxidblooy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjbwyjle.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtlwuomrmw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtphvwxgfc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtuhspgybj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gttkysmbdt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtxddwyfmx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gttyvswuql.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gtlbqscsyn.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gthvtabcgm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtmxedcjyl.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtfvvwuytk.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtggshdnue.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtsbomuxao.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtvaitlcux.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtijntydfz.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtrlngxmof.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtsxhoznrw.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gttushnlvn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtxntwqrfm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtdexidaub.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtoprpijnb.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtxfsrsgkt.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtqgumlukt.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtabqyjjdb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtqywaiitf.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gtopfkswlz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtphsxplyx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtphnqjhof.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtyhookcqh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtretgkcgr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtjbzqipxs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtwdisdnpg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtxlstllbx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtpnebwxvr.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtpqoyyjeg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtjvxfesdh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcjfntoa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtrgywukbv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtdkywtgcs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtannucgwn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtwbpivjrd.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtvkyeooet.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtdzojtlzi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrkgptlqv.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtfsdwrkrn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbxpcmbkr.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtmzzhjqvn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtklumwbqo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmivieyhx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtwghghdma.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtyaxzukcx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtbpkjmiue.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtqnoworav.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvzgujzai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtazwggchs.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtgokmjbuk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtdkfxvmlw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtlrdqaseh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtgtwshlbg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtsavqlemn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gttkkdiihw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtguwwbzkb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtmdrsleli.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtzsuuvjrd.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gtgduawkvm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtvkjeswkw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtboqzibcn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtblzqpbqx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gttoakhrmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtxvzfellx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtbzxogyhj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtuozueinr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtxunmcckn.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtaoxtdzzq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtcvfvjrsl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtykqisjyh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnizixyav.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtodexrpsl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtnrfreabf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtzxeunqjz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtabinwzpc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhkjqqro.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtulksjdxo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtbrpyzlif.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtpkwqxjfu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtkccwterg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtuncywymx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtzegtyjcr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtrtyzejnb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcqwsbxzz.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgeaeadjc.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtszgkgonk.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gttrdwjjnn.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtqesojnaf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtrcfnkrvw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitwkqldw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtoeufekey.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthupczrvz.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteysjzgwe.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtqsenbilt.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtavdsybsn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gthghwiqqj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtkoemlvhz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtrhqhxibp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtkxkagltn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtpjqqtmlc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtoxitieax.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtsppfzoml.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtvktxhzno.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtjjutfvme.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtduwnwlwe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtkemobqlm.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtegcryfcl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtemgdxrtw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtlzddpscd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtwbfhsnrx.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtfwmhorrp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtnkcgvnur.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtlluqbfhc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzqpppaab.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtmvongxjz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtklzwhuwv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtawtyqzms.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtdqobrzia.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtauvzwohy.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyrwutsgk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtusdfqvjh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtoenegqit.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknrppbjy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtpwrwmruu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtrchaomlc.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqflczwjc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtmcxoviik.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtmrnmtjoh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdqngtvto.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkrdapklp.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtsdgfupxx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtxhznluoq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtvniizbwe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtalsootvv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtabatoktv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtcvwlntiq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gttzstvuqc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbzsxhjaz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtcjktxjfo.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtpptnjfrc.html


<!-- 参考信息 -->