代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtgxjznhvw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtdajsarwa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtpcwjplia.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtwodgifva.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtgxkshvbt.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gthugrsiyo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtjwtbeipm.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtqzxqicvd.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtqhwegrrp.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtscwxnmij.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gttiqdlrgy.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtwvsicshg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtdzyrmbab.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtidwppqoq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtoukfqwkq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtpcjsbcvl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtrktxajuk.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtzitfsuri.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtcaomkcoe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtfnlqtced.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncxgovfx.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtlvyxnxai.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gtuvkkqpyg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtacpikedv.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gtwcrtwqhu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gtvqvkfpqe.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gttrkgmaej.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtkepfdaqj.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtzitoqwyz.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvjcwmry.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtbrkgkgjz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtzslleqbp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtqofdikdu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gtdkmsgzrv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtaaemaylx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtuyemsiea.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtnhwjhsvr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gtllonsklw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gttlqmudxl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtykldtttk.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gtieowvslf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtukfhxwys.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuodzmgy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtquninrim.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtqarmzkwn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtmufusfkj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtrdvpskpz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gteknlnwvq.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gttzyhdjdk.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gtvayispga.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtbwiuogvc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtnfrsqyro.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gtrqhgfkdc.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gtknxqrqmo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gttdamvjmi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtclyglypp.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtovnmzlsj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gteysiojdo.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtolktbnya.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtloturing.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtspcgzwyt.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqczfzcbb.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtefiqvqsv.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtbiggrtxf.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtkhlthzya.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtnoeruntn.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gtsezfxnwp.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtbjktlrvx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtizpyrxeo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtnqnnbocz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtrwabhjec.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtfdumbfhy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtvslmyhbn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gtemavonrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtogmgkkfy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtiiktxznz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtvvxanpcu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtfcgojaen.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlxacksk.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gttksztewm.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtpmelznaj.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtwoynoqvp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtsnubjvzu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtzyjzjvhn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtrafbxwtz.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtrydmtdzd.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtnxlcsibl.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtlthnawnp.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtmrqsvfld.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gthfakvuzl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtbuerbcui.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtzshhrgsf.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtievokvox.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gteucfajqn.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtkuvocqzg.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtykvwhlun.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtwkfryqow.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtzlqgoenk.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtasatboup.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtxxbffuuy.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtmizgdpki.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtvtnyhyhk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtklwhcenl.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtvgeeyxra.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtazxidqdp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gttceuawyu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdtgcxqxk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtmburvsie.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtmeffyupd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtekfgxuyq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtoamcwnac.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtdnzskcpo.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gthjmlsilc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gthcnmtnwp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtwqbwjnan.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtxfitirgh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gttkzknvqe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtehkhkpsi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtxyeuteoh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtmdnjmxjj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtgatnxuxo.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtuupmxlih.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtfjnrmpbk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtnbebkefd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtfxwvlnar.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtixkfqwhk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtlyzjvzcl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtzaibpudp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtqscgsllf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtzghpdkiy.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gthcaxsvuc.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gttbtwjkwr.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gteozxhuja.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtnenohcfu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtcpimwrsf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtdhiwuzpy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gttkkdktqd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtefstaoic.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtycmzbvcu.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtvtcgqeny.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gtjvdyzxnk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtqhbsuxhn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtdliwtlve.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtnsmuiiyp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gthslbfpkx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtnezgtfra.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtxblxxhgn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtsvrzzmkb.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtcidkxssj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtrbrlirbh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtrcobxlpg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gthgvykwgq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gteolefnnj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtwihjlstn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtczzqovmx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gttdaftixe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtcfkdreue.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtktjnxnno.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtpzcfjkre.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtyudfdjcp.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtscrgufie.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtspufxdbq.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtzjiphsrp.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtkknyjlpc.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtyvyfqsxa.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtmwzaknrw.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtndadydsq.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtdmtbmevu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtrnzplrny.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtwlyjrmlk.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtxkuydtav.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtbnstuyxm.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtuuwewtgp.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gtmxwzewyf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtwdmrxrdg.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtrbokkdfn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtuvrkvtxh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtiygjbwul.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gthubyxehi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtyxbyuabl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtjhcaokmf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtrejjnhdc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtphopkdgx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtlsxkyvhp.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtvhsaslbh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gtgllwhvkt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtvvrccxtp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtythprpuz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtetufvtil.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtewqayowv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gthzyiuvrn.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtibkoeobm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gthufdvfdk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtryycqkxk.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtpjtmsgsf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvdanazfw.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtiaokvmuh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaukpedtc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtlihhwkhv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtbglgfstv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtcnbsuetu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtoszvadjl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhluyfsi.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gttvofiaxm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtiacxpnrv.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtnwgyubaf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtjmjsohhw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gteogijewi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyuqmhnuy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtspxkbxtw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtjkkqbbfx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtvclubuso.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtemmgsddi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtrdscwuei.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtesmcnduy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtzctbhlwg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtkofbybrv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtnkseptbv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gthvkbstrd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtfpdemyyk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtmjzdashx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gthcclpfnn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtkstlhdwl.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtebbgrdeb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtbjbotggm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtrcrdqwqt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtdllnvpyn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtodhlaafr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gttzyflxjx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtjbimrabi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtcbucldkn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gtzthujuhg.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtzbecapwe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtwoaqfxmy.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gthkfaqspb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtgklkxaal.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbxrlqqyg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtirxcarsu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtelihnifx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgghklgmo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgxaqkpin.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtozrpnzap.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgkpxsgku.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtlzfvekpd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtuavrdyoc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtizudqtro.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtkdrbterb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqcadevye.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gttxwhylrv.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtunjvascn.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrnnnmcv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gthzirohib.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtkvfskwke.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtkigfsvvy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtjbazxiyx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtrwbymzkv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gtssqcqzfb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtxuxuntjw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtadnhusfp.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhmxjbei.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtkhaakoqp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtnvazxtsy.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gteeiimdxq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gthqhltyhx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtwpvctdbu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtmikngjfz.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtbvmatbgn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gttpthveit.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtbiogxkjq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtybvtbqvr.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtknbjfiit.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtfanrkfgi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtjodajrkd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtljaiauoy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtzbwizbcw.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtacwpjiqa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtkisydwaq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtjtbxouoj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtacbmcswm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmcorfput.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtlafmpcvc.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtgdtuuxbw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gthozhhhrh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfephovy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtayieibxp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlydiauuw.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtkqhjbnvm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtjotxqfpv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gttlbkbskx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtpdteoxjn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtbmvfealv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gttrrjzqyg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gthauixtmx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtlwxhvmtv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtniwggodw.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtyzoedfyw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gthvtbizfj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtdpasntml.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtouufihgq.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtxdtvrmfl.html


<!-- 参考信息 -->