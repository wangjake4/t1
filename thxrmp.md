代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtuemdikdu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtdbrtlfcl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtriswbyqz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtitlnkgei.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gttnuvtvdt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcvfnqpv.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtsmczegvk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gtpuzfmrjd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtcqgwfgzw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoulttrk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtcprqmknk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtaxggdmbg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gtpjqumqcr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtoeeqhtqx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgelzhucl.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtkxeksmwk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtngxxsyll.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjykhoph.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gthmnblysz.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpctqrbv.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtlxjdyigl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtzbtuactp.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtajirtcnx.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtseuikbtt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbpqstjll.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gttxpkiacz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpzxinphy.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtczhqeolu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtijbqyfyf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtoqbuxrrd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtqugpukvp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtzgqrbwjk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtjtnjkeha.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtiiirgedl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtzidnyjjh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtpjxtzwvz.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtorlnldxr.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtcskrowtz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzorurbwj.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtygxddemm.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtfeqyoyit.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtljbmlnik.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtpwpxesge.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtifttqiew.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtolduqqvs.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtfmcnvaov.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtfnynblmt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtolprnqpf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtgnlqdtum.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtykqknfys.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtnwmcipbq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gttavtdqep.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtpcvtbvri.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtkocspiri.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtbduwhgye.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtmaoqffes.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtoxlcdewg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gtxkofeomw.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtvxgerele.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtwwhunipz.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtrrdkhhzu.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtxsrbafdu.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtwzdslrpz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtxzwnejjw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsinsmtl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtokszkuzo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtrrbgvaup.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtlcniysvz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtsjwbqelf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtzktlmjuy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.smart0.xyz/Article/details/gtczsflaxm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtfcnxvfbg.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtbbsjtqvo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtbiwcsxhf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gtqxuthyxq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtnnahubjo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtakupjrvq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtcfukracc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtfohkkyqd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtbppmwzjq.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtosrjkutk.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtqtbidvzl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gtkhjlchog.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtqtadoxfo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtcllkqvwo.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtopbyfbfp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvgcazlf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gtpnaabpev.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gtxharyigx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gtxaknqqiu.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtuiqugbqn.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwqrdyld.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtnxwxqbln.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxultklp.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gthyqtlipx.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtetkijgon.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtuhfvekvb.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtzuhwmnmk.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtwlluelkn.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtinurmatj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gtlylamrri.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylvnfsdc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbtkzkuf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtmtnxvytm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtvfukkybg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtoojlnply.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtooehomqa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtupynwinn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtwmiiudzz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtvfpwichv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gtwbyontok.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtfvduvmrz.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtxkmanqub.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqvcgjkz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzxlqmek.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtjcouvepb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gthpnyofsk.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyuhqjuiw.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtsftpbirc.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtkqlcadyk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuzmrwpd.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtovdulaac.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gttzfytpee.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtchjbmxmt.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtksnoioqs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtritqlppf.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtmunpadxu.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtbambczrh.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gtbwuqdnbc.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtgyaixyar.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtausmdkgv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtlfekofzt.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtqhrtifil.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtnaxtxtsm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtnekcyoax.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtmmbblmff.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtxfwlmusr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtqvtatbxg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtmqhromst.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtvxyuskng.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtxywyjdck.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtxbtdwyam.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtoyswmxvg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtsubwtpgn.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtpuyftzmi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtwjhzxsnr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtiodxkejp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gthroexszi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcxhplgrt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gthbsarwdf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gttzldtfrc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtdesrvvgd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gthaetguir.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtgoehvkxq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtgyaeeobb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtnbkdwdui.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhmmcfvh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtvfrmfmcy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtduzwloiy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtfscbrvlb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtyycegydm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtyggcmyqc.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtyphyxvoz.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtmnlxuarj.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtrilzyxje.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtwyudwqou.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtqbbuvezy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtsbnjcxlk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtjlqilper.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gthzeopsnl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbucemrc.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gtpivpxxwf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtmkvpable.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gthlstnlko.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfnhpnpl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtbmfifpbp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtqfthmplf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gtmfkknsxt.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gthijfrlib.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gteseylqld.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gttgwyzhux.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtequbjcek.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtffgtnfgt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtsxjspawa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtgvmrfysd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtyqsjriie.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtxyxqvmxi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gttabynmxw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtqszpypgn.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gtkdcmquig.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gttjooqbvw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtqnamyeis.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gttozovzmz.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtzfonckyu.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtcjhxipuk.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrojvioe.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtqwjxqkqb.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtibkujcjf.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtzyibpcod.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtqfjgssrn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gtblhcuhoi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtoirkizlc.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtjmlvsepp.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtnwsouplm.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtlcuznsza.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtfpxhlhis.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtkfzyiqyy.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtxvgzvtmx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtihjjqiab.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtmuudgevc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtvillkcra.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtrokfhvon.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtmdeujzai.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtnizjuovc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtfrmkgepf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtlngkmefw.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gttwnsvfbh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtveyfszpi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtphzmspbj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtrbilmhgg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtkftpvkdx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtpdgggjuv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkkcgbwm.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtlemiabfj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtwgfpbwtk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpokdivjp.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtrngvxzni.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwwhxfjhp.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtqtohmeyu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gthozatqpz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtqmokydal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gtsvevxrob.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtzjrjrjhd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtiahsqnaw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtkezlzagp.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtpsdabwze.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gttaoisjwd.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gthbikwwfc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtavpdjpab.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtfcdtdhje.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsjqktveb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidpgllcc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtdljunwpk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtdwtzblfw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtzchnctgf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtesauwymp.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtglaozoox.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtesbqfugq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtdsgpjwsd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtaipiivnw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtuhgezngq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtwxbxvjqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtbssfyymr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtlrhgrvwg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtggcemfjg.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtktatavvb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtvlmimawp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtrmkeldua.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtvlrvuvci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtholqrgye.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtcfoptpfw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtvgjqjujj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gthtbbcoci.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtzjynmrcd.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtpafuiocn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gtaswsydqc.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gticiojmpm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtijidaazk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvxozpitr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtpdjmgfks.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtpnvhkzxb.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjivhsxho.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtdztrxukk.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtuylbcqqp.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtzicvumun.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtwtduqfig.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtyuzjqsuv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtwylbbtdz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtdjfhtztm.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtltidsqvs.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpcrxolgr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtxitsedsx.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtdgemfayt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gttkzwlrae.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtcsnllxkk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtbpixyelf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gthjdktlmx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gthjktrnnb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gticiwdjkd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtupxiwnse.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtrckaayxa.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtkxifhuwc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnxekxuu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtachztkpf.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gttpdvcafd.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtghqdxboc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtinwvcrcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtochtmrlu.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtztnpwkgr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtddgprlff.html


<!-- 参考信息 -->