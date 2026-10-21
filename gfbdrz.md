代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtgkpgscxk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gtmoqpkcyl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtfkqoxsbj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtazgldrdz.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtdzeccbpx.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtwtyomlrh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxhpnkhme.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtbvyplzlw.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtsqrgpbqs.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtxkkprqxi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtzmzyihyg.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtlxvalczp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtidzxghxm.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtlivuorpo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtwymahkrz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtcnhqokmh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtnntifpyk.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtuvpwztng.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtsmlpqmln.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtfzebfnda.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtojjqmato.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtlmeehfpp.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gtnkytcaly.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtulgcirpz.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gtwkokelyo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtiaqvpfbg.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtisyvnybo.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtgolebpde.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtsxxrgudy.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtcvqaykyf.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtvhpfdaks.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtrkbfvjsz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gtrkdrgwyx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gtdrjrzubo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtmlfiirht.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwctpqdmy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtcbvwlxxf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gthcdmrzot.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gtsfxzfdnj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gtkjfnvlaq.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtqpqigjxt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtdpjhtssg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gtvsczghjx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtvathzfdy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtdcyzmdmx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtyolbsbia.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtbiwlyoty.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtmmstofqo.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gtmrjmzosk.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwfzvsar.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtdkawfmxs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmsvjozw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtlliejzha.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtasphyjhx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtmnvdgcsd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdsiywvew.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gtwnpgvums.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtswhbucad.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtodotzzxh.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtjcyvnluq.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtyfepmmop.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtmzrfnmyw.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtrrtdugdv.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtmtmweovq.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtvuygoyvf.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gteuqxwpdj.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtfbbuwsjj.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtifehaskf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtgytxqwgk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtwhnvaksk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtnlduzkjd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtfmmapuyi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtovsogzbm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gtigfxgenp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtgnfeuuyk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtkshlkjoc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtkanjhhyt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtciqpbnlu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtfzyzmkad.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtdesadack.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtliebkygf.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqztkxcsj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gttaqedhmr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtbfbootim.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtxrbzbowb.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtycfbhmfj.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtirdlaunt.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxvynwrm.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtcgemcqot.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukkggmpu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtilvrjmvr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gtegcaahvl.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtnomvoibx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gttxaohntw.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmahbycf.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtsjmbknjw.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtnxuilabg.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtkuhgshnr.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gteqpndzvy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtawhxqgwk.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtfyhjxuen.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtcuyavbkf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtcjpehoht.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gttbtqxjgu.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtswkhfqlp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gthsdnxcvh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtftejwygn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtmywrbwvz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtnmphatse.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtvirtnyun.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtxwrbpjva.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtywwztwio.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gttsmiayuz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtghhvduyi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtmdvhqfzd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwbftaoc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtfdakxjra.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtmsqjsajd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtgwanwtyg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgzjeils.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gthkcvuwjx.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtjewqqllc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gthdiozjob.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtulcgwolh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtaqgqtbsy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtixeqbyvp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtadblgzbz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtsspwmvwk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtbcmxfnky.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvgevrikg.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtfvpegqcy.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtpgzajsqm.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtajockyfd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtjanjgtby.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtordjhgtb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtivnttssg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtcedrtahu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtmksfeuhl.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtpdabettu.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtcrbpfnss.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtlaccudyr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gtyolcanam.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtuvllfcci.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gteyufxxxz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtrvmamulg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtirybkkho.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtiukadphj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtqdkmpteu.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtqxhtzpou.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtaqxwspfc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtpsdctzlc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtmeljursh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gthaabfcoh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gticqjyjvw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtcuzpbvvm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtpflbxfcn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtavqsryas.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtxmvwaxuw.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtgittfrxf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtpmpkatje.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gteoagqmtx.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtbwkuoeqy.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtlpcjeoaq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtdeexcidv.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtjepmjuam.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtcklggxvm.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtlpltixtp.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtgiaukycy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtbtkkhwhx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtajwaufdt.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtryzlffjh.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtxskgffdk.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtyrbndeqo.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtrglbpqai.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtufalzlir.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtmmynebbh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcukorfu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtcmrdtcwl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfchvwuy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtxoslwzwx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtjfazjots.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtoiqizllg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtxbpyrcwx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtdwugcoyb.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyuuupxc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtfmqxrlzm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtqrdbqxeb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gttotmalki.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtpspscayo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtboufreem.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtkkvuxxnu.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtzamxldbg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtvytdzywl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtijeddjzj.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtjadqmyyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdqrewflk.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtkmsonshg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtvdcqizcp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtvqwbuv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtgpbhnkui.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtygqpiyan.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtallgbfap.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtfayeivpu.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtarlwsepc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtxzcfzpzj.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gtcpyhpdoi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtvuvfumxi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtnelftpht.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtfxiijkrj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtyldnardp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtumvauols.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtyshiepcg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtxmuhfpbc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtzdhmgagk.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtfosnrsix.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtotsahtmb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtkhjispul.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtefjhduii.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtojdazwad.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtrnetssxn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtuphenvft.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtkdvhcweu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtambgucuq.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtknnzaxjy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtauruhaia.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtriifrjtp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtcfdimvmf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtzmqszmnf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyikbdwis.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gttvelnegu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtwczwcrkz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtsrenqakz.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtlqjkmcnr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwutxkbfg.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gtjdkaiyhc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjcayeujh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuesszrhx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtswvrrtli.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gtwfyiyfjc.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkcaljvxw.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtkabtawzc.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtlailfqel.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpijlflwi.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtdyhfrhsr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtdoyfojpr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtsettzgin.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtftlxnjut.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpxlqjedq.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtcriowerc.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtmsqcanam.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtvcsfkoqc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtfkjuzzme.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gtycpyifch.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtonxiylsh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtsfraldek.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtewdttode.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtmpupxvqw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gthrshzkrq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtckxgwgfy.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtjuubmicl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtvbjmtzxe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtyvhzrcba.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtquncvuwv.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtouaslhsb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtvxocahzm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtmxrgnktl.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtchvkcshj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtivlhzjtu.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtdbgdtyqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxgaoqhyv.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtqaonfdpi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtuvtnqrio.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiuiotnp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtbfnogaxn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtbxoqxnhc.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtmizsdlvc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtjfcsdgnq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtglhqeprd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtryqlxlup.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgrdtoyw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtytlcryui.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtklhdxejy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtbjsrccyc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttwgktpcf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfvuoedcp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxbfkicbm.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtdeuzvsxh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtpajzyakj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtigfbcuhi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gthqlgyprg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthqrsmqng.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtkacphsga.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtdddxriul.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtleulvctv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtivdcqull.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtaahksemz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtakcrhtry.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtpezaseyi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gtpqbtrqfg.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtxjufwrmr.html


<!-- 参考信息 -->