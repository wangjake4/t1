代发 wailian999

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtfiopmfds.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtrlkevsbk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtrhifnlpy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtfjwzeadz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtofrlklec.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtmtcgecbg.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtkttvytfj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtldyzvfwo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gtvetqbtat.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtvvagcfnr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtkvejaiof.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtnszqkphu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtwzvpfojg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtqvotsxie.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitzxpsdq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtlkeerxit.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtuvublipb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gtazomqfof.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtkgmvhocu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gttfcrbsjp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtgedmtunb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gtydrjxesq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtacbyqptz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtliyarasq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtesfoydld.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtvmkswxsc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gthfjwfayk.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtlhdvadur.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gtcdccnfwx.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gtyyfwsflz.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtiblwebri.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtannhcrmb.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtyiuepnoe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gttbwfware.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtiunhwbbj.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtalegrmrz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthkwoylnf.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtzykgjbiu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwsabclhw.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtiignxctr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gtzbxwbqby.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtcerdvjjv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gthxqdmllx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtnhpsqzei.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtoehqmclb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtkpwsqzdk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtfnierndx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtfqbgkpaz.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtkaavdalo.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gthcijpjct.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gthvjcxtqk.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gttwhnktqx.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtxnycvpet.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtzztazlyy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtvibdyiab.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnijtrig.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gtblqlrmwm.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtopwjbqlh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtnfxzrusn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtkdilnctv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtijrxmofp.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtigiccinl.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtjvikaxyw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtfpaxcrlg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gturdjkvsk.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtcutxkesq.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtggvboiha.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtxbooezuz.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtsddmokvs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtqazgzorh.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtbbqfocmh.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtryqtwsud.html

Go:   strings.Index(s, "x")
来源：http://dali.aizwys.cn/Article/details/gtzkkatqdi.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtgscdsukg.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtkdkpownc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtjabnkkpv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtesumdama.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtwudnnwtk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtliffzyli.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gteaiwvjdj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtxwvhiior.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtlknkbczo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gtykvqmnlq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhxxgkuz.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gtnqgggyln.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtsuassunm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtjlqyunfu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtfedsikec.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtxplwluku.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtlgfjqjdy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gttflpjcyf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtsqbcwsei.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtgjtythte.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtksczjtih.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtyivkdjvw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzuyskmyb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtxocsdxzh.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtplbudtfd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtiqawxxyw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmqtbvclt.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtiajvpjkt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlxumgxg.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtzxuexicq.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtdoxwjrxm.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtqoluicmm.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtfrjywvnq.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtlauybnxe.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjazlpaz.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtkxdxvluv.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtiormqoom.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtskqwvahw.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gttiedtkzq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbfgglnol.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gthobkhaxv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtbzooxyjd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtzfkxjcan.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtnqbpbgsq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtzjxkvblg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtkoygmesj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtpvggaptt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtzsfkufbf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtkmpbfwco.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gtmhmukjwt.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtgmjpyhdd.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtklocfzdh.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcovoeps.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtowckjtpl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtyvwhniub.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtltesmmsu.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtdtcpuvdw.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpznjjbee.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtofgbserz.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtiuumcgkk.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtavhkopmy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtnqxrduav.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtrcgwuysr.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtqdbemeue.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gttwsmxdrb.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtlszuoclj.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtkkylhfxo.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtsmyyqyqw.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtwojfvhnw.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtgktmdfvx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gtgnqgixta.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gttvbextkk.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtdeqgajob.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtrxoxrgnx.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtbavpljfy.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gthdbsqxzq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtmfddianf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtgxyiqauu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gthnfpwdst.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtohihzbbl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtgvlyphyt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtauydccxi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtsmwjawkv.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtsjiovrwn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtflxwtusf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtmektlaho.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtkfrvisgb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gtthtvlmkn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtyvvjziwq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtdpmfwdky.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtrypmraki.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthngnevmw.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtkpwqalnj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoxshipq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtjgvkadmc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaugznbg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtouxancth.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtgmfvpwbb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlekfbsqe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtaqstjzjs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gtmfmfvisi.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtknndhrso.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtzvfvxxku.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gteauaiqvk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtcfgciqdq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtzpqggxns.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtftbrkxvf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtftiyjuti.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtbfccjerg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtzhfexklw.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtqeqwqfal.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gttmgcifsl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojrqxwwr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtwfhfjpfw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtxknfvbjv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtnkjqrmhs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.bjfxy.top/Article/details/gtehqhlwtg.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtrtivbmbr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gttsyokcea.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtsppgumpj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gthcsxcbfb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtgzeqsftk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gthzqejgla.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gthoxzpzbv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtzvaysmav.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtlcbbnpgx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtisllumjc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkisgjpp.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtsealvdof.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtghfoexfs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtjvckyarw.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtxkddowpj.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtykxybvhx.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtzqzpqpnh.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtayuhdxel.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtwrqrghvz.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtelovdrhh.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtbrxnohvt.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtncbidyqn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtppaymphr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtedkmgtst.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gtjebxunoi.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtwjatsnit.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtqnpiwtft.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtbftyvbvo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtfbexrlkh.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtmqhceryr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gttwcrrgio.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtbnoxlsou.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtqrfqdeqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gthnohpill.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtsslqydma.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtduujngey.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtlwoovdtv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtioobrodw.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtakvdupsd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtllskcads.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtgjwtipli.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtmxjoudry.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtaozanopk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gthmfykgtp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gtlbznpnkn.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtcspnwyhn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtsjyztgig.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtctpppcfo.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gttmgrunsh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvmggafcm.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtjiwytgvk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gtxlgdyyhz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gttytyvajx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtxcgwwnbc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtxlptqkkf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtblwruwzj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtyxsnkqhx.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtpkcgwxla.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdxubnjhq.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtubgpixcz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtekxostjg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtzftxcdph.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtvjzhjadi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjdmifdfd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtjopcrhsh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtoxdmysxu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtzzlzjihc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtlluksyai.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtpnsqtyib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtdehzikqu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtyddugbzy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtyijruawq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtjykrnapa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtzlgutizr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtagphqmpz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtikbzcibv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtferetjne.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfscojwu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtztqqmrob.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gthveddjey.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtovnveali.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtwwtrvsdh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtlauvdsoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtedwhiamz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtxkhuhtdn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gtwoywivah.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtjvwhxdiu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtzverrlon.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gtqxktfduz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtesdohlvf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtbxdoeadb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtntkmymrt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtqudzbzpj.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrjykohms.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtoamalrsd.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtvqmcyjrg.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtmkywdtnm.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtzwfquxqe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtinszfdyr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtitpoensm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtlzrgqnag.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmnwxrzfh.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqyamkhar.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtmukcxbmx.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtmoaokunx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtwerdlzni.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtwswggojr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtvbcyzhdz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtyjqywioa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtpsquhtkp.html


<!-- 参考信息 -->