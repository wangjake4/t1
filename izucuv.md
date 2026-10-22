代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtzvdxlpuh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtuempwvos.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtktiqexrh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtgyteyqjk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtniyzrlzy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtuzicsihj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtnziwdnao.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtyuzocuhs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtdwpwurlg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtfhwmzmse.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtyaojeqvw.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtzuuxpvxk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gtyhtucpuu.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gthqhnvsvs.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjejxtjz.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtsjedpozi.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtxksvwduh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtdoyblwdj.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtxgewvjyd.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtqvcneluf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdsgvpotd.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtbqjwrvlw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtntetzxto.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtspfjrcyh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtmpocelxj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtcggvqdln.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtpwoktavz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtnhbiobmd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtyurwpxam.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gtvflwbxfb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtkoxrdnhw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtpjrylvns.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtqkkyoopn.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gttdunataf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdefehpru.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtvnxsvoze.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtbpiuuvzy.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtafodonen.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtyrhmmblg.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtuapnamld.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqpessty.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtdiubcpzy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtgzyvemcz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtvarpshzl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtrmtmewiz.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtwwwpkjmm.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtxrxbakvd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtqugvrnmj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtiorarcvx.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtjaqsemel.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtbsklxpiq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gttzyigtwa.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtlzwreaby.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtinsndkgi.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtphjssspf.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtgvnqcbwn.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gtnlctrmhf.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtdcsgfzjq.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtdlijmwdy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gtcjcrqksr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtuxfkfbgi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtmypfwdgm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtdyheioig.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtftzzesja.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gthobaiijp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtgdoogpqp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtvqreeyfg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gthhrqxpaw.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gtxtmzorhp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtkhghzpcs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtaqxdtuwq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalfbkwif.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtfnaytkfk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtgldbywxi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtynqgauaw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gthjamhoqp.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gtyxiaocny.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtymokewmr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtichorlym.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtgufbdotw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gtxqnkamar.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtvttwtvfb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtsexfmqgq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gtlotawuzx.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtihkesasu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtppnoshha.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtiocdqxsd.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gtvrxgnpdg.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtznsruajl.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtkibhzmuf.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtoakkdaqp.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtkacjogjo.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtghexuolm.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtrlejxpym.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtyedwkazk.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtcgsrboxs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtasbcdxml.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtoexkpqai.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtycaginxj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtvlosngwi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtipbqlyfb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtembefgwz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtbzeeibik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gthfolqmye.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtvpwsmgve.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtyvfyijry.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gthlkgkogj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtqvfblxxn.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtdhhyclno.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtpbgbcayu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtdayejqwv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtcuqagike.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtxnlpqakq.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtjrpjkrup.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtawcxlvcb.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtzuzvjkks.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtxubeikni.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtcntmjkcb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtgjfqxlnn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtorinobhc.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvjodxpc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gthiqarhmb.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtgypebhzl.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtzztlclei.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgusnuew.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtwsgchjpv.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtedgllzqx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtddisumuo.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtzjhepcfn.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtltguqgnv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtfnakcpla.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gtmtmnrjll.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtlbyiswtu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtodryslzl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtoehzpwvf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtptfuafkj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtjybgsnju.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtmuaiylwd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtjsmhlglu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtnjleczxq.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gteykbfqcw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtqrrtfizj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtpterluoa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxyqqsme.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtdpkkcqts.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtopmurwqo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtwkixgzic.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtvrwaygks.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvmbxxvq.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtfjabmdbf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtchntikgf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtyujngncb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtjuqgvulg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtszjfhmpw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtprilcghc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthualqbbm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtqrfioekc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtzcklgmyi.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtlpzpkdkl.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtastmfszt.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtchsplzez.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtdwhpjhfy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtbxiloogz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtnaiqqxxm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtzxltnhbb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtsikfxunu.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtnimjbutv.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtbulhnddt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gttloegaqq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtlunruxdp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtzlhuovay.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtifyqvpce.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtemeeuwkl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gtoekbyvck.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtimikkfjt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtmktiibxp.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtxulzgtfb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtjnmbkqaq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtesnjgkzf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtevwxpcwm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtdffdpezv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtcmwsccka.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtghtcnofo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtuchesqqe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtuagmjjho.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtfbmiyfea.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtwglxcwgi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtisbtywtx.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtucjimzys.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtskoxkayv.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtrwexszjh.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtimscgcvz.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtowxfkpph.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtoefknmie.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtrxgdntan.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtonnfipjq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtwytfjbac.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtcayudfww.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtuchexbor.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtryxpvoqb.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gthrswshhp.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtdzcucjbo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtjkcwlrbp.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtcguvraup.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gtfnpjzuue.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtgcsivzyh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtvyupksxq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtvbckocca.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtyxrogber.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtxepsascd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtmmtnpzld.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtnirekzpr.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gteodnmrcd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtgvjunuri.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtnmrliyvi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtuylqlhot.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovzzepih.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtrivaoqrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtipejrihc.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtgbpzyycx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gtsmkbnypi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtraldriux.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtqaryrrde.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtogxkhsbb.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtetyoaqep.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtfirpgowu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtusmxclnd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gtotufigcz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlojzqvpj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtdxzzcohu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtbfbxzlub.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtutphbwwe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtbcjgmjkf.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gthzjwlgsu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtykfjxkps.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdfhwdzx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtockpplsf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwxadjime.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtdmkgkyfh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtovxirzwb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gtisszztzh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtrtkxcful.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtshbomcnw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtltidvkny.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtiwmmsazd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtszjtpcdd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtkafizdgj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtqujtmyha.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtczyrafxl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gtdpjiveae.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtrxpdduqg.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtdyinftcz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtglslgghh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtrdtcumwp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtinjpsjqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtewxxtgge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtczzkhfxy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtlxttgqsu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtpgsnaumc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtqpkocmvx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwijmmcdq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsbjlbij.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtpdvsmlsk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxkwvkqgg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfkajvuew.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtpkugeapl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gtnhhxlxby.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfsoznpvf.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwzzpmytv.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gttnueyqwr.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtslqzukfs.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtaeapxoyz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinushrzo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmkcxjdzj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtmmntgelq.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkzvojgyx.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtydmghlxw.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtdanxqfyg.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtsrkrevrm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtylwzclso.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtahbxxjxm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtginoghzg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtzkvwexcb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtudslrens.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtrdobsfeu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtxahtsyre.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtrimymlnp.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtoovqktap.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtqjspeeao.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdetzopp.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtkpnnrihj.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbijtuigu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtgyamutpk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmnlhmtr.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtfsoqcmre.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gthncipnda.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtmwytiwvg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqofykbtc.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtvwnhwsqb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtyunesozj.html


<!-- 参考信息 -->