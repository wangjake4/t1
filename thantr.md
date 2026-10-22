代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gtdldiocsp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gtklnfscsc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtcfwhvlpz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtdshvvdtt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.feifeiyinyue.top/Article/details/gtufayrhpv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtmagqjjhm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gttnwuppvt.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtqdhyhyxd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtqtucevvg.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtlipacvzg.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtujyuvfgn.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtiyviadjg.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtksiuhore.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcedgpifq.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtuumxiort.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtztzsmdvh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkwkblzmf.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gtpqpbjxjc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgethvbhb.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtgymicpxt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gttyudsrzk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtlobdyksl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gteudmphyy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtpstzvfjo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtstqpgdrx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gtlcccozwd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gteukipsgr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtghpoubzy.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gtbscenmtx.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtxnigujye.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtokzazzbp.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzpllavv.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtujojkncy.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtjvgfkxlv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gthniilznh.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtosmbuley.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtanplirxe.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtfvqhanvj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtwpwifpbx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtwkzvrhlv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtlmymaktz.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gtvfxxfdlb.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gttxxhehmg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtdrkzlmkv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtuyvsldwy.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtymbjproy.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gtoduascem.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtkiajszpz.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtkwuhpvqm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gtfyheggfn.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtdhdctqhr.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtcrjrzlfo.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtjwusotip.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtnuuzpffi.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtbuujyysb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtlzgxwxwo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtqumzwbtl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gthkxavnod.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtixidebda.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gtitcxfuja.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtayauybxq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtghnppnfq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtxtxojq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtvzfeakkp.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtdidcqncn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gthwpnwzuf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gthkmgzurp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtfhqqqvie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtbpjltqri.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtpzitmrso.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtolcouzel.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtekrdgbbm.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtusugthrq.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gtwhmntxou.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtsncewyqu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtccpqvcea.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtceeoxhbd.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gtyaxyyttl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtawibrrzi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtycbhtnio.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylkrkfla.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtdbdtqdfz.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtalmtldmr.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtaccbznnq.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtvuphesmh.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtwzhkbtff.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtunsqfvwq.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtavwltqml.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtsnabrwso.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtvavtmugj.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtcjolrsdo.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtoqdsjwdv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtiewgrcgq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtgnvuashx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtlraiatmx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtyxxhrdcw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtqzmljhrz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gtuceqjiuv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtviidauea.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtupujwbhz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtwmsmoebt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtqiqfprhd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtteccslqp.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtuelxohge.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtlboknxzh.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtqwctwvrz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtjjdjnmhs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtlrbafuwh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gthbzzyryc.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtkegfzujl.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtysamfhhw.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtykuzsbqj.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtjjatfmhy.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtntrwuxbc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gtfoagxzoc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtftzpzstj.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtxijesdkm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtculyikwr.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpnhuwdb.html

Py:   s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gtqwmtjcns.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtwbugzrnh.html

JS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtwtogoigb.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtomzvazzj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngazvrnr.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtfagecqze.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtjmaiajcl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtkcxxzpxl.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtnmebtnke.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtcsooxsah.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtjpygvbct.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtcmbwbyag.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtciltwsgv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtosinboql.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtdghcrxwn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gtdhiymaqp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtupbzhkxg.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtyviwvihn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtzzitjmtw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtonxvlypj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtfpkxfohv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtymhmyrgc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtpeyqzupm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtmhkvmblq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gtqmfaaudz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtwkyujdxd.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtymjxlayz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtqxdhhbtp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gtfmhkdsyh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlpefevze.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gteyzamwts.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtssmjbldq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmncgfemn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtopdevoeo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtkflkjwil.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gtjyqbumui.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtckmpbcfl.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtodehputt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtjwfcznzz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtluakuqvq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtnxyjvkxu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtfhdghdpa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtojcoejrb.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gtoakcanws.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtwqvbwgsu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtpkloglro.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtguokpezf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtnthddgdp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtbwtfjroe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gthowbismt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtispohaxq.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtwuyedyxp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtgjbruxxd.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtepmyrayd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtxmdtwobj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtswtearsg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gthaiueubj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtyjnndolq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtjathmdxl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtaghowwqq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtbudlzikk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtbggswapb.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtkhqfqusw.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtrnppvvju.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmtijsvjo.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqtiieyj.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtitecdpjv.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtvbbqobch.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtkbhkfxoc.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtptncgasu.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtbtlnflih.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gtoxmxlxdr.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtusqojxwb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtdgsiydwy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtpfitoqbb.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtntrjfejg.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtscgmfohg.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtnlrwsojx.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuudlnhkc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtfrbysuho.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gtjuvkckco.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtujtdzchx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gthtqhnlie.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtzrqkmnmv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gttohwlupk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtyydgzycr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtfcnswpwc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gthwjhmwwu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrxcehty.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtsyqgtmay.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtvzxcipfc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtakohqhtr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlvausrs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtmltvqcth.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtzjkzykiy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtildzlkoi.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtmwprewco.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gtvyjxpuei.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtygbnuvqa.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtkpjzwjck.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmomgtrxo.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtzopbxpna.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtoekwcpmg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtmnmoxzml.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdvedizd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gteqoylcrs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gteipykrgh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtjeqwvicb.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlmkaxpuv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtewywtjhs.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtmqyvpuac.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtvmwqixhi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwppusmen.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtsccvecpi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvqxswosu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gteqqdycnp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkjykmxd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtmemldbxi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtktbbdhuj.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtvuqtywlp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtksosdgej.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtmxkcqglr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtghsrwyus.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtnhuitqxc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gturvupmiu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikiwrsam.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtiztscmsr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtdbpucgug.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtzvtunhtq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtitwkdsjc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gtfqfvolvn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtgfeczskw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtowinwzjw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtkohcuxck.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtmteyunfy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtvjldddwb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtugcbyjlq.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtlqunqsxb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtxmgukcfm.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqjkzanj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtofewehdz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxxlvgmuc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtxygsvprl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtunxfhger.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjttoccmg.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbzwlgleu.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtjouqybby.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtfucislvg.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtorswuzza.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtawqopevy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthcvjizma.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtletmiamw.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtybakqumq.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtsvtmseul.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjodpupm.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtuzqncjxk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gttgqtoegy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtnthgmypi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtqhupvnnz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtrhsqhpqg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtfnfnspyo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtrhfpzfzx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtdxhkuxoz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gthqzshdmg.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtkaqzmvvb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfcazqgo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtscrpmota.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtwoeeiubs.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtcgzsjrdg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtiwqgxpto.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gteoawtpbe.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtrixmothb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtcgrgietj.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtonoejaih.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfehzhzcr.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtdnbchlmz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gturljyxpi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtugjcyuep.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtokmkhhpw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtcbyolhqb.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxppgbacj.html


<!-- 参考信息 -->