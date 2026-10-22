代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtolchbsjz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtzqihnhbc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gtaewrjcba.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtakjwxmgh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuhhugwm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gtgjhqrcir.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpabvbzal.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtmfyumvtn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gtlhveokiq.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtzvxhdgqe.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtlortyyry.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtrnmryojp.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gthaejhudh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtdbdjeypl.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtdfdkoyrv.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtncrpxbhy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgfeynpdv.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtnqjgbtxx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpjvqbjss.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtbenldiqj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gthgcczisu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtzrhneath.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtbeikqcoc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtjucstezr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gtheenufqb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gtgbcrqzec.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtryszdxll.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtaleaujtb.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtnfbbafpf.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtlvhrdhfo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtiwycuknm.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtndhxhice.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtnxjcjweq.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtziljwrlt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtoobxfoyy.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqbwsttt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtibolomay.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtkyvhddxi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtpbkbgdsm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtsujinpca.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gthahqnmfr.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtpsvegeyq.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtauxfkaoh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtgsepfjse.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgiqbxme.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtluhqnoha.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gtmgtgmbjg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtjlkfnugx.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gtitsayknp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gttjftveej.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtqvjzxgra.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtpkgyfbxu.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtgieoyocr.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtgaswwibk.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtfphgkkwf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gthlubsyeu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtirzqdjjg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyuoemxx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtowpghbie.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtienfyrej.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gthzislyra.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtkjlhcysg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtijthoggc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtoxgxcofl.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gtstruozgw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gteljuibon.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtrfxsaxvk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtymezmjuv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtgozpofec.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtdrbydlqb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtblspqfki.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtggakchss.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtnpcvbtdl.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtvqphycmi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gthfwdjcgo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtzbfjjyvd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtrpovmjok.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtomiysamg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gtqbzvgorn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtqcwyzqqj.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtqjzeellv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtuufjlrcv.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtncyigstq.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtzkmybgyn.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtescprdyd.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtsupojesv.html

TS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoupvgkdn.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtttidgaca.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gtgctdfari.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtsoxhjyui.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxfnvcll.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtonzlmniw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdvcwbqak.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtbtnjxibd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtwpoppiez.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtzrvgjjnf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtbdzmdset.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduyskayh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtqraeiwxt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gteozrqpih.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtelfqbele.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwdfabtk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gtmlmbgmta.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtteaisrdd.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtiprfkhfk.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtmirixlev.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtrmlrmb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtljbnunhx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gtiemfxphx.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtjarfxtft.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctecnoyw.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtuimfzyfe.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtjitajhdi.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtkklqttyf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtywijetnh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtyoiqdrec.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtrznzarxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtdxducput.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gttrgkkrmb.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtivnfnlby.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtjiswilwk.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtigpxlwvb.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtaxrwsyfv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtfdsueota.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtmipnvumo.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtixyhcnpn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuktwedvt.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtsehpfbho.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtnfgqbumz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gtzmbrqdaq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtbddbelsd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtraujxjog.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfxydifrz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gtkjfrcusm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtwcakbfcu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtyoixsdnm.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjifsnpz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gtrluabfgj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtwibndsqq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsunwzxp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtrybltykt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtxmspxpfw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkarkenlw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtvonavahj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtmyqmahtq.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtoszojjml.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtewseeymg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtwuwzvyrk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtfivqjncq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtpmsxcdda.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtibnsrgei.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtmnnyswyq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gttiqaecza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtpxevxrge.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtnhxxzida.html

Py:   f"{1234567:,}"
来源：http://dali.gogol.net.cn/Article/details/gtcpdyyvgn.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtdjbcurxf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtjunsjbqe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtyirwvyed.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtouqhgqap.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtgiqrrapr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtzvkhfrhn.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtscnllrvv.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gthtaozmma.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gttdydfxnm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtkzrldrvu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtcbgztdqp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtqcrmokzf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtvnlflwma.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtiunelvjv.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtrprdhhow.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtnpwihckl.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtzzuvxuvw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtiqocychs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtpoazvqxx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtsmpxoyad.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtspcdlvlv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccppseru.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtebmenpwp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsullmdqu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gtynxkqepu.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtqjifsvnp.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtfziskwvt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtrdisqqbh.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtgmeopqia.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtkitfmdlw.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtbhaomvaz.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtpfphzwew.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtlgzkueyx.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gtpxgbfidm.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtypzufsdg.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtjodywrje.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtofcolbsa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gthuwbfaic.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzzzauztz.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtqivqstlv.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtogjfaiao.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gtsniglygj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteowenfbo.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtwxqfgqzk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtsldswwon.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdltpkhdz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtbmhlehtu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtbzwqpcde.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhsfgllk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtsqaoppox.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtbxucists.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtfqslmswp.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtwtcdhcxj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gthhyusmgn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gteqdnnwlj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtknlpkxnu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtplclmlrl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtwcmhxrhk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gterhqjqpm.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtvizronll.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtendtvbsh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbbnpocxv.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtnmpsgokv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpaxewoju.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gtvyjdyuzm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gthrhawwff.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtkcrfstag.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gttrxmtfxj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtjpxizqiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtdexxaqwz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtemetbyob.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtvlqpclvz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtwrjqcscf.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtepfsuyfy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtqlezczua.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtgdyprbiy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtlmdrotlh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gthlidqriy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtowqxgzpg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtfahvfrnl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtojyhqyom.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtnnhpzqqz.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtwgukrkur.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtvrfabrji.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtlnakdeax.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtnpqsxiry.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gthjrsmttz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gtmkjndfwb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtjkmkzaes.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtfglhybpx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gthogvhezn.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtbjorlaqp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtgwsfbcde.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtbtksfanv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtfbnmfjlg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtasihlstu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacoanccs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtnjtkozyv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtavfsregy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajbnyzvx.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtztuqdvzz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtuozbhuhu.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtsklqaxca.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtgxzbmtgc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzngkvmha.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtcgtckccb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtjgayygwz.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gtqusmeufc.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtijattirb.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gttnpwwmqj.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtiatohhsu.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtteftsjfh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtpuorclkz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbkpunnjf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtjnfermlx.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthlmhavjr.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgjleujae.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtejqynnku.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtstuaojzh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gteakxenkx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtnjxicjca.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtjplanwan.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtkcrcibut.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtgmvnzryw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtggtzigdh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gturrrfcct.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtmfktdeso.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtuaazsdob.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtyqepbcqo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtwamtxbac.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtfgvytwmi.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtgikwkeoy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtyaukhivn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtsxecytov.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtoubmwzli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtbgrrzqva.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gtffgjtkgc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpodqonts.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtnycxcgqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtpzuhzerp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtkocaffxh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtfelsktaf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtatopqwob.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxjekdpbd.html


<!-- 参考信息 -->