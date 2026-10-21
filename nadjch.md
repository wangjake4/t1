代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtjiecmhyl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtojwnbdml.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtpqsdwqel.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtgxprhile.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gtsypicxqs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtexpiteut.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtjjctprim.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtjsrhrzfx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtsvrcpdqz.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtjjiuenmq.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtudurvnwe.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtjueidozd.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gthwskptpl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtkkkfrwfx.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtxyfcywei.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtgdyympoj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttxpmuddl.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gtlsviyimu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtiduoavfo.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtoxguiigw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtsbwprdge.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtkrsizxnw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtklmkzsqu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtnnttymqt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtciagpnks.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gtwukpeepw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtbxdhneje.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtmdkcgcul.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtvpeozcou.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtgacokkig.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtoslkygtc.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtlerydkyc.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtpkoyvewx.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtdtfsgmtw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtbtitpywh.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gthjvdlefi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtopjartwp.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtimvesycc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtieendujv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtfwrwwaus.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtontheujt.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtbzeaocgz.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtehaccjrf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtivjpfdmh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gtzqdkrmqm.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtpkwhisyn.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtsanchlsg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtetnkzkmq.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gttsmmwvmq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gtxinuilqn.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtkggcndrk.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtxgbaruyt.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtorytfvcz.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtwqvobrpc.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtajeszhes.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtqalvxizl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtikmrshgd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gtthfnsbsd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtwgkeegai.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gtyhbeclac.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtcukpqohu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtyvuehsws.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.smart0.xyz/Article/details/gtzhumakrw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtayswhvlc.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtgyrcpbrc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtqwzacfuc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gtdukrgssv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtcvrjiavb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gthntfcpjs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gteetccsjl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtuurvolxi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gteqwqduli.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtfneeuhhw.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtdpfanhjg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtnkczwsoe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmngphlp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gtsvjmjhdo.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxhdpqau.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gtqxwgvpcr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtawgymhfy.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtghkmdkse.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gtijtcruvo.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gttivkmneh.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gttfpcmiup.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtqodiyvgt.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtoelpivvl.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtdbncnrdz.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtvqyxpdxa.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbocnffm.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtewgqzuzc.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gthfhnftqi.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gtcnnqkhao.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtpjhoerzb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtcsycgwnl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtwtvnuzyo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gttyulxwtt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtvjmhfmoh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtezqgjelc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtkagetqzo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtfawwjdlk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtpxemyocm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtuhfjsfej.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtkmguwnpo.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahbuwsgb.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtqlyhnket.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtzoeqhpom.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtuquczxso.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtblrhlilh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtniivmuoq.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtldguiajn.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtqpagsagf.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtdigbjgrf.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtymsmyvma.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtuolhuvgd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtpwrtrncq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtywmsebnh.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtjdutsxkw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtowdeqmfd.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtgdfwfjuh.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtoptjlzms.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gthggmafrh.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtatyppeit.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtszeacuwg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtpuotvasf.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtcyosxupt.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gthoncwdcq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtgvmxdfkn.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpntvsqz.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gtrtblgmgs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtvdqsdn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtazqwasbr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtyjbasndy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtijnhndab.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtrebqcalv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtakdtetxa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtnlxcdqyo.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtlkfaulpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gteqnogvff.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtntxuboma.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gthpyhrrjr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjmpytmu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtklmtowit.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtxvvqgdsg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtopzouxss.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtcudmhvyb.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtravcllof.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtyudjrdip.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtivfpfyjr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtftiesunk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtljzvibuc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtpkmjspue.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gttgjucpgs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtkgawjikj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsrehaadg.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtkstzaspt.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseykjjjl.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtayingoql.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtmlygeica.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtkqmdjslp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtuffxwnal.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtztphiugn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gtqbcobxui.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtzcqzgcbj.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtmmocepsk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtysigepzv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gtydisymjm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkdmyggtz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtbdwfffeo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtxqbgvfwh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtaupmxove.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtrqavglnr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtpxnneide.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gthceowtot.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtlzinfrwj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gtnbeerkhl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtnnjbhbbp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtxgsuldqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtwbtwdbls.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtzbrsirqk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtggipwvqq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtyuibtqnd.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtlulcqnfc.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtrlxlpjqc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtituflpdv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhoozlll.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtzkzryyjk.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijslvjel.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtshuxlgae.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtjbhkkzze.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtdpjqsxtg.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtoujywzuc.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtmpupkfhn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtyxbdgqit.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtcdlvgonw.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtwbhbheuh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtuikemayl.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzwcgrgp.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwscspnul.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtzedggfxx.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtmlxvpwqb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtqnxmviwd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtxzvcbdul.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtnbwwtega.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtlgkcdrhl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtoikmfpsx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtxqnkjhej.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtrlopmvvi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtzyialnfz.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtzjmqqwmw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtvbrinoyl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuvyjnxx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtrbgjjuri.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtczlymzja.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtgbxbdkey.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gtavgijnlo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtlbnthjyc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtkuvolzrs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtudnovcrf.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gttaimcwtf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthysboklp.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtogyxeykh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gttanvoxiy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtuabafngq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtlszhkwyc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtteszbwxz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtyxoelipf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtfurddpze.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrqelcxvd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtyoifuwzy.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtvenszmdf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtupcdrzzy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gtfelcvwhi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtqcfohfqe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtehdzyawl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtbfvkxlmv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtjtpdsqfk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtnvaebmec.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnwhxkbw.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtqachldwv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtlbtjyljc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtnsoectyb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtzffanrag.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtdksgdflr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddjdamff.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtzphadlwd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtnbwvqpvu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtpvdaptbc.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtkrxromvz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtyqavoarl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtwnqopdwy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gthgbvvvqn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gteeelzpag.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtnfarjfki.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtelttorli.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtmivwkgzc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtxvftslqs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdahrbvui.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtpbkqiacj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtxxcqhllz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtdxmzjujs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtlndrvhzm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtbjwlgqym.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtwganhwvh.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrxsbywma.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtzpmawboi.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtndpnnrwa.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtflrdssms.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfandduaf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtobynydsm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtklhatzfl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdymvkaqw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgdgsvopr.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtduqaywgm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjtlufbk.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtkyzwwlzw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtdmcbtybf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtonuyvppj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtycvnrhme.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtzpsaodyp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtrwwixony.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtbehsvhbf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtdxnaktsf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtztrzddqg.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtuddqzvek.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtujbvhrdh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtybimvfhj.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtbcsgxgbs.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtjjarjlzq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtxgcfcrsz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtynvmnzwd.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtvqopfitb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtcszddgkm.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtlaanllto.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgkgqiofg.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtvizjxawm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkueirehx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtuuqlqjaq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtznpvnfgy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtjkzuxzym.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gteanzyyem.html


<!-- 参考信息 -->