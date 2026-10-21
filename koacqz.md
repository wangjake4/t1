代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtpdvdwcij.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtsolomxrg.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtcnpaehzi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtkypyccmh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwxnbpel.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtmajeiqca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtuorddgsj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtgzahbtvl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtnpamleaw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtfiwomaqm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gtmexkgnnr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvennmdzu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtidoglckm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtlcwazibd.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gtsdsipbvt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gtdofavimm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gthrquufql.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmctlfltq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtdrhvnxge.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtduqnlwzc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtxsjemqrw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gtptharfth.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtfzwnheoo.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvlxxsku.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtaxtsrzzg.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gtljpyrstb.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gteczjelfy.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtdzfgoxzw.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtgfmgvwxc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gtcdwpfwhx.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtlnihquaq.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtaioxzcqp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyvjfassh.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtutcivxyz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzntaoaup.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gthplhkppm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtgvddhlfu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtzbwaqvvl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtwnttppfg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtxzicnafn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtkxqovimy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gtibycsfez.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gtkmntgccs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtcuqshxze.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gtrbsqsqjp.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtpsvayvya.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtxocksdol.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtexgawcsy.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgvyldrr.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtkusojsrl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtjpyxdgjt.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtkzlamigg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gtdtshymoo.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtmeqcgdsa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtklzvhajn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtxrltpzlb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtguusfenx.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtgvxwgarg.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtxquqnvtg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtdllmmjoq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtdiclgbhj.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtpmviwuml.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtbivwoxek.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gthpkpvftp.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtngdsvsxi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtkltrrfyc.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtaspfkftn.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsnvaspt.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtykpxqpqe.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtdowsslwx.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtxdxknphj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gthrwaavhk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtesfxysge.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtnmecblio.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtkzxlvkhr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtxfawgsfr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtnxrofwkb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtokgalcga.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtcglxcmjr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gteoyzqplp.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtpftykyjq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtynomomos.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtivoybjqr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtpfcpmxvp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtfoharghx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxsinvpdo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtgbuhofrr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtarubhsrb.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtlcfesiwc.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtaviamrub.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtssdnefdt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpewmmuay.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmuunalx.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gttdtjesao.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtehfyxzgx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gtecdyurpj.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtsfjekfjd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gtyzukysei.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gtylmqjhcd.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtqhxieion.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtsqmnwcdx.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtvavczzuh.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtzfnqcvyc.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtmildqfwx.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtkeudhdlq.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gtboebvayt.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtnzcoylsq.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtvsxlouxq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtzsaueqxb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtvixjipyv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtqfufcpfe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtckxlbgje.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtpvkjsxaq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtmhxikdbl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtdnoihpsr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtiutrtnai.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyknuaxf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtyswhkcvj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gttbebsmck.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtnvpyrhgg.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtedfugkcm.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtattxphnv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtyaffygdz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtshsyjgvu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtcjgxkmpi.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuyvatmj.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtxzuvrszl.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrmqkfci.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtrioeandd.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtasbqsxjp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtzaenwvjq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtouratsqn.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtkvxhsppp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtfblqsuie.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtriilmjgy.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gttzlcwoha.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtmrkazjll.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtkzabnxbn.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtilfoawnk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gttzbcotuv.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqobiall.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtlygcnhwb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gthkfidfep.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtlcxtnusu.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gtlhykxgls.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiwudspz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gthlotfbdl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxspkbmea.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtsxmlnwxh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtwesgizwm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtpuibqvpm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtluejtlua.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtweurcfvj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtozfenxxm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gthgzlcehn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtbraxtcky.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtbecjjqoi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtszyvvbth.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtovbxzmai.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtzrkjyyqq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtqduvmisz.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtnqgrosqw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gttgtrmbhd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtjxtlhfvv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtzlvlvraj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtxnghnvew.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtzandranf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtxnmxiqvl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gthdfzukmn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gtrzslxvck.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtzslmykdz.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtjfftcene.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtzsgknhtt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtqwxgzoxm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtttnhckya.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtceggqmxo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtdmrxqaur.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtdltnnmzc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahyxtwgx.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gtgasompcr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmygqcarr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gthelpjqsa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtakkjooij.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtscdyevqi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtsquutcnf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtlegvgkgp.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtkfxpyqyj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtqyngiler.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtvgwdmhux.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtrzqjwpee.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtmldxjqgf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtzbhryqdy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtrwcybqfm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtmjzkjqdb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtldtpchcx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtednvppaa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtoqygpehr.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gthwnqggto.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtducbhfim.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtxjzstzzy.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtnupqcfwh.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkmxzbyk.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtulwfmycz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gtddgzvpnc.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gtfplgeeha.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gtexzcrmri.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtwnatmewl.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtomokiuoi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtnedkehkn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtkbzagurp.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtyktwrxym.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtffrcsxzm.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtfcjhmfpz.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtjnqyyxrx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtarrsjzdt.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtikyxqwfj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtexpopprr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gtqaahwplb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtycwkqkfh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqayvxln.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtfgaibnsr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiamdylra.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtjwkbyiwm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtdgftfljb.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtjstgykxj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtqshxqzmw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtftwphsfs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtjcwfgifl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtlvhtdxxn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnghypfz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gthdcwlvrd.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtsehbbvuo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtceqmxskk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgxpppcqx.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtjzszdtwv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthuupocjp.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtjuuaznjt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtrglsbizk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtryllrdjf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtpdswprsf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtdieldyas.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtfixfdmak.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtlrzrortn.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtuniltrzt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncizxcvn.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqriupqgz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtbtbezlcr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtzwadkyxd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtvlgpydhy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjnzsoegs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtekyysevt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtspibkljj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gtsjmkfbtr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gtndrhruae.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtzdgvhrzl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtbvoagutg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtvigpbotc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtnlklbmmi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtpezshsjh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gthtyfljmn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gteeadbobx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gthhirduxz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtgqiojhqg.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gtseffypbq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtsgnxhaed.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaafxzzt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtgmddywyh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtrwtpbfgk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtcttokrep.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtvabtvapb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtgjixhdby.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtwxhadslq.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtkaxuluky.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtxekdoqaw.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtbfdlmbzy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtffbmwwnq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrcdndnao.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtkebudrfs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtulmxfhzg.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuxukhsbh.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtthtutwqi.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtcjpwljqh.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtboroocrc.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtlbtijukp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpbafqzqp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtoznrauxn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtkzmxeprr.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlizithcn.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtewwcpxhs.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtgtuseeaa.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtxfdajebe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtkxgujkpx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtqpbszaho.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtcekvsawa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtpamhmeil.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtgdbpirsx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtrxvckkbj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtrfnvqeth.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtvamoapid.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtuzjpaetm.html


<!-- 参考信息 -->