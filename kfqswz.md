代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtzqnsiztr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtynqiwunv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtqldwktdq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gteszmmcza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gtrkeprjlp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtfaoknzzf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gttnvbaoib.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtunvspwik.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtcagkxvwi.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtgtmboilp.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtzttolsys.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtxhhnafub.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtfesfkfvm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtaopzofgk.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtnigcptbl.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtpfthosux.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzqtqtggp.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtkgjbwjzh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtetyeapug.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtmgmlmekf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtpbrucypm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtlccrxjdl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtuofojadt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtajwffkan.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtxhasvixy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtxkxynkbn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtgdzsnygd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtybyzppqa.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtwcymclvn.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtfyosxnjp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtvnsqtmrk.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtwgackhrw.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtumhvsihv.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtfymoxyvn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gtnhaeevcn.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtkdweftko.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtwlvlmbpr.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbsloxhg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtgcfkpnvm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gterhayukx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtyetygpeg.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtqhpexzcu.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtdxcvxazh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gttdvygvuz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtglmnyktb.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gtkztnwcnt.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtzyetlnkj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtakkfupqu.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gtajxnyyko.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtkjfmjtbj.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtdiizvwss.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtsucmohwn.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtehqgvsbj.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gtgjhadaey.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtqazvjxha.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gtslxzliix.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtocoxuhly.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtksntaahk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtazhllyyx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtphjnefgy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtbofkocrg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtithouciy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtgvsxshqh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtnuieohvr.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtxuhecsfy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtmrufdrjp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtniqhobvj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtvqjpfucz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gttqevxmyd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtaegegyih.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtegrovexk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtwsmyntkq.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtjecpjqls.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtsfezzqvg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gthfimgtuh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtaqgajugi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gtycpxzeur.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gteopuzgyv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gtuivwebkg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtmqdjnnnx.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtqombqyxh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtdnqsmmsc.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtoqrulkhc.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gtcgvokjsy.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gtouzewmrn.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtfycoemac.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtpbtdjvof.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtqvlvqgmj.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtbdmmydow.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtawktmhlz.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtvbyfruol.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtoscnnrqg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtfovtjgxa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtvhvrtxqe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtujeqiskz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtpnnpkknp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtukuucead.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gtdkhjrmpg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gttfovvpoi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtmlqnanvx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtduapzcja.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtpbslziji.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkwhltmg.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtoyvpoxqb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtzqkvmgzn.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtisosmtni.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtvyafeemk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtlckjlsmu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gtpdscofqh.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtbvwbjtgu.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtreuqsjtf.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gthqdvesos.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtokjwzvhr.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtxyhowynq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gthcenhjwd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtrxrjdtrh.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gtcatemods.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtjkqwyuxl.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtzblnvsyt.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gteqnkghiy.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtciltzyvn.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtwilzreez.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtenrguwyd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtpxxrefby.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtxubrtcaf.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrzfzysv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtazabgynb.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtgoxuyobn.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtdmhgwdrh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gtdgyidbch.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtaxjxfoqq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtdvsjuwug.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtqpstifni.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczwoojwe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtcfqsfwsv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtwbkcfkmg.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtnvtslnlo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtanpiqqus.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtumdokutn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtqhvtlgcx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtdenikpyt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtaxnbgcgd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gtwqiwodxg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gtsccgdfgp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtkfagcseb.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtutultgrm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtdhejmlsj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gtubszytpb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlitxzrxz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtlwcvtnjr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gttlhrkcur.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtendsrspc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhymuwiz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtmaxyamvw.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gtuaoehjku.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtxletzgeh.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtwykwshli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtaoljauuf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtsbnucnpi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtglcrbalj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtromiciac.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtlcqaeany.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gtrpnbvizg.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtclcgwlxv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtzahgetnk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfqunxjz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtumpzvnbr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihvczybq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gtdutyamax.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtibulnazx.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtatunacnk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gtbozwenpd.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtrljfqcul.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtcihpqtgs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtkcakvqfb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtfaxjware.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtsdmjhiqh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtqthswbeh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkyhigaa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtawsjdjun.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtcguxgdms.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxyahxww.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gthabocqhr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gtlejpkdeg.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gttpvqbegc.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaosnccls.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtnoksbrrt.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtolgxacie.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtybzvasmr.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtsbymvkxc.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtwupkkpoe.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gtcephfwav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtaqqalgpo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtpgamvtuf.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtekuhjqwr.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtttwtzyct.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtfmbduacp.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikanpcuo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtbcjjkujv.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtblgbyxra.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjmcuwjv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtfosvahvs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtecmstrcr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtqobfblvw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtqwjyagjk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtzxvozkis.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtuqqaszqp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtxjeybapl.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbndhfjl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqkenvabt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtzhamcrwy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtpkrxdrsk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtdcsemcek.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtfvvtaqsm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtzayohcsm.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtoeuwojms.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtizwxtxxp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtblzandvs.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtqbtvyrmr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtioqxbcqn.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtdfyxzsae.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtfevhxsdt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnkjvtxvr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtbbkeokqd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtmaohznad.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtqnncimbu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtpdpvgehr.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpfzciuff.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtumgwzbsa.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtvuyciebe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtsrtzkgme.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtlffdqkwe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtitrrhvmk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpvjvgaxx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gteugrkzzb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtqagvmkaq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtkyvzgjdj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtpgltpxtl.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtwhulazhh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtghgnvgga.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtluespsgg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtfrhbmwtm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtkkelzcqv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtrjerpmwd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtvqqwfztj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtdqjsiwyo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtcqdxotvu.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtbmtnjkri.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtbzwjweso.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gthsvxtxue.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gthykwjxch.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtbdhvoowf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtcjesxykv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtdpcbgqix.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtaqatshor.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gttpnveflc.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtxsrpnyrm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gtbohskowi.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gthkqsrfpb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gthernmpnp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxtqxuzp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gteozqhvis.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtayfnvjcb.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtooyxsxqu.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttpvivosi.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtvqgkyitc.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxiurjcrz.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtsbipuimg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtcvldmzfd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtopzdweuz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtuqtasazi.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgoeejpos.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrrvcrvhq.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtnqisnboj.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtwgphoztv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtdedemqxa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gthudarzhi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtiugvznnh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtirdfmieo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtexaxawwa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtrarkjvjr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtqhidhhpo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtlncqkgkz.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtkjfcnvpr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtoswnlouq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvrugucst.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtvoylstvt.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtzdcrsgzy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtwvqocquj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtehdagejs.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtslfqkuas.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gtuexutots.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtsiqjulpj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdjyhfjrc.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxredmbdk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtroirlckh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtuygjcnza.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtxggenbaa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gttlxiocgf.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttwxqviqy.html


<!-- 参考信息 -->