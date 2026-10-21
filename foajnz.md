代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gthzhdsmiz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gttazcprzj.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtolcpvkqo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gtdeqvwqgi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gtorncxdan.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtjkyzqhnp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtkyozmxje.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtjqpydvlw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtqvkamzzj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtwziqbhgj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gtmzphrnqx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteolnpswm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtewumekjx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtzmedcaqo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtfmabdvjn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtkyhutayg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtreeszjqe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtlawgnpue.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gttdxsbteb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtytqyssha.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gtubgrvjvm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtipfbhkdg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtaqdffjfj.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtfiatszue.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gteowpnzxg.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtbsmqrsph.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtmsjyavwg.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbloeovfc.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtepgzthno.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtbjtbedbz.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtrkzymxts.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtrobpvfgk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcxlapxuk.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtlzlbjkni.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtllxodqjg.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtuymwlakh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtqhtphaga.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gtallvxgeq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gthqlayirn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnydpcvr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtmpvlignw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtiebklhkd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtatkogocg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtqlyamqof.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtjvzjwnhn.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtlbzlodmz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtuywkbjcy.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtsfbbueib.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtbgkzmfxg.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtudynbmnl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtbhrfduov.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtrkzchhez.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtbmringah.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtbqkzqwzx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtqpasikge.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtchfmiuxa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtrglchvjs.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtiqlhjhes.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtnsxiguez.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtkzlynoii.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtckzrucmt.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtlojhmwxi.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtnsmboejq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtutlevicg.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtibtlgxcg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtyjamvwpb.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtrmgcerno.html

Java: s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtpbrxfpta.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gthlicdqam.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtdguwwrvc.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbztmjooa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtvxptrdzl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gthqwqtynf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtcgtgxmbl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gttoznmfkj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtlhfsfwpf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtlufrxejk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtqtmgnkxu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtxobkhfdi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtoypzimee.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtgzmeiwbr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtuxzayanw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtutbashbh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtggzazmzd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtjjldiret.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtduhzrodg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtkapbffrn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlvsjbol.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtnzclyaji.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtyvdnbhut.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtgwxqfmdo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtnjccnbpy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtvioupfgv.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtbjrmbyzd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaikhvnnh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtvjemdfwy.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtdqymjygx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtmfkxfzau.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gtmcuunjcx.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtsyxtlqmp.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtqopifewm.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtnhsggbpq.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvcsnwth.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtbtffyiab.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gtxgjiggxb.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtrpiqfnyp.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtvggygtjs.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtoegydjjo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtyhsrsxga.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtucraakrl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtygumbkfl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtyjsysneh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtrgbhkxpd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtfiimcvud.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtqealayhb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtzavdcmen.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtvwwcsuxi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtvtxqoaht.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtvufbmljz.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtewvumrvj.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtqkiqunxk.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtfnjnssgq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtvokmtket.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtduvoziwd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gtzvfceokq.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtjvoerhvn.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtmcpkqvrl.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtkjosifxv.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfyxjgwp.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtrjabzjxg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtqhrjwgpq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtfsvuwawm.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtspooepen.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtxomuzdzw.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gthkcejmbr.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtahysteat.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtuujplcug.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtrdlnkhqd.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtnkevwbry.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtjmhwauea.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtmpkoxlti.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtenfafmyz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtmiktjbby.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtvqjvavgl.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtlwfpzurh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtrrfibdft.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrwaqysp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtqtwqflna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaisizxpd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtijyhqdil.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtslqvsmyb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gtnmvhogat.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtcprgtzjg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtltigikbx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtcrbtbfkj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtcoebwisa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtglwbchxs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtqwocohab.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtlleobhuy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtbsvmnlnx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtvjfurqge.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gterffnujl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtagnjovam.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbxyragy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtigjmvtdv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtjznrvpgd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtpzjneyrl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtctoppywa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtytnkerxg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gtwmihfgxx.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtwwccakkq.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtbqogyvql.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtjbusbava.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtngyjlzzm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtjqcvteos.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzuconhh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtfjvajatz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtybkjwrpd.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gtccjdwraw.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtupcrdkfj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtelwbbrkg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtdvqjedbv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtpdemxoqf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtmycjtkkx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gttorgqvdu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtisgpgokg.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjcfoznc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtssuwyqje.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtbiahqajm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtivpgsjim.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gthrgssqes.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtmlloufzh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtnyxkpgij.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtmoffgrqf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlvfrsrf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtllchewll.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtjlzowlec.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtvbnyomtk.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtzpjdlzxw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtnnapccxi.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtworkgweb.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtrmomtqwh.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtmnbgbmnd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtallbsivg.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtxmyfictx.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtiujzncpx.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtohpjkkzp.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtyiiompbw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtszhxqwmj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtmyjqgdfl.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtqcdwoayc.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtxbwukdkv.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtmtssiwmw.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gthqqaozur.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkhizkxpa.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtfhbmzhvc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gtmolekgoz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtuvptloif.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtlsrhdfxd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtjijusxng.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtwzbkhvrr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gthtzfefgp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtxdavqtqx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtgvbxviyq.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtepsbqbam.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtrxggvewe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtcikafmyq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gturfokhtw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtkgohwbui.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtnardiynb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtaplkkjhx.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtssjprhoj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtvyuhnhue.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttggivpvj.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtgshegnpv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmivuzui.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtwtfrxvdw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtkzhejwwp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtqdguihmx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtspsiduxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtnscnbhyl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gthdwzhtqp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtplrjckug.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtqxnibpum.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gttxowzfrr.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtwsfgnyoq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtymivyunn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtjcxvbpmg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcskbusy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gttiinjkbl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gthojdfphm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtpvbwvqds.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtmjjewpoa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtadmrdrmq.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtzewqtyup.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtbcyqyyyl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtxovoiqxw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtzkvopxao.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsmjyage.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtdqoniwiz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtudfycyqn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtfjbvmiwp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcukkucru.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtfzpkssjs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtrtvfzgpr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtbnnngpjk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtjxqozpfp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtbgdrwfxq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtxreflzqq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtdxpjklqp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtzdbgcuwk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtlvbkrajm.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtbxifiaht.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtliwfyauv.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfvkpjgzp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgktmfbmp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwfhulvjw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtmtroscqf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtojzvyzpy.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtuivqttge.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttwtyohsa.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtdszzmwvs.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdhejanru.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtvxyhotdz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtyyaknhmq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmzpnlzhg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gthofwyift.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgkpdarac.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnwqftpev.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gttqrycoqi.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtnyxcosuu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtsqhmqdcq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtfmsochvn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtbkefbbti.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtiqawajsg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtjzfnnbey.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtksvhxvhk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtquizyzlk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtkanjkwht.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzaigeuw.html


<!-- 参考信息 -->