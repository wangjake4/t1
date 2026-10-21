代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtgfwfsjms.html

Ruby: arr.include?(x)
来源：http://dali.jianghu66.top/Article/details/gtsszmabga.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtzsylonlj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtmbqcfvlu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gtkbrtwogb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtibmhopsx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtfynlmnct.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtyoiukfpe.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtwoeuysrb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtnmyzignf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtxyfvdmlk.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtpkrisdqp.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtvnwfswfm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gtgkeqvbpe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtztqxwuqy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwlrqvlm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtdnvkbzqr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtyiywljbf.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtfoxoddnu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtelfztyfc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtksdgtmar.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gticteviep.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtqduxvpbx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gtblzxxqwq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gtxuvvmxss.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtcnlqvytm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtlghqjkci.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtutotnuxr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtgkunzxxv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtmniclcgz.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtcgxgdlyt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtznifdzjl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtiyketjap.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtnoyupazi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gtqaitaylr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtekyhebih.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gttcrauvar.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gtprstzima.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtmqjxdkqa.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtxskacghx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtfpzyehhq.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gtriskiuro.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtykvlorpb.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtufwypbdt.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtyqbsnqrn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtndznygzg.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtdfhcsxde.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtlvatorly.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwhmaqvxj.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtzrxldhww.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqreukxyx.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtrojxtmoh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtrvvslsvf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtggemgemx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtqnbhbzci.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtuvbupkzu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtczknhoch.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtlytmyegi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtiouibuhw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtjwqiosuw.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftrdrtxz.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtxdofikzq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtvcnauefp.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtatqvlirc.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtfeimfebm.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtfpakfdqx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtywhslqfx.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtifyzxhwv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtcymjpeqb.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtlajpdxla.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gtaugqklmk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtuzilujqr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtxvhrtkjn.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtdqgzvvyb.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtymouigaq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtswduolrm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gtrhhmghdx.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gtvzepowfr.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtpuvdeueo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtofnrcjtn.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtttrowzpq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtmfudfsnn.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtezmcnsin.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gttxbdiqco.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcniobukl.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgxvqqae.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtrpsvwliu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gtpbeaalxu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtybvpolvz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtovzjplxg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctrtrprs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gtseoqaual.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtuqiqyaiz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtzheymbqs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtxurepwpu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtlxqnszmz.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtazkgwgfq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gthewtnwdg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gtllzfmrpy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtwqyrwrzl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdotiwqh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtcpyrrjrd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtojxwkojl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjflvwtkf.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtyonrazwl.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtlncadtbl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gtwtluxobh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtbyyajlgm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtjeauuwwc.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtzcbzfxyz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtudodxccc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtxfjjefus.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtgypvvlwk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbobtwxwk.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gtlqvopkjt.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvtbqngx.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtgkmavoiu.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtvkqbraua.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtkzloqxxs.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtxxsplcde.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gtbsacnxwo.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtpqwdfttm.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtzsepwtyu.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtbegrblfs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtomspblzq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjhfjlox.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtowqupvdz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtswobhykj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtygjnisud.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtcxlpqwjw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtnhcewuva.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqawjxks.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtsesifkfw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtzmxawskh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtacmlhuhz.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtcyqzmvqv.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtjdpxxfne.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtdnloxqyu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtgsnlfmsk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtkyisykni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtlyfvcnwf.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtmcteexqy.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtprrflzlo.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtrabfiqwf.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtqhxvwdem.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtcnxyjjeh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtxpeyrryg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtwzmfftqy.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtcaxoanmw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtfmprxvbj.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtrrwljyzy.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtphkimogr.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtirrbbhuj.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxahpcts.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtfobiejdd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtpwlkffgq.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtpfpeuiuk.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtkvxoptbe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtukkqhaeu.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtbwcpgjdx.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtudzhqiax.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtbdxduqiw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtagmxqmjx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtvdbatcja.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtbnmpywgt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtuxqioehu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gthclgweik.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gthfwuphzn.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtoqlktmqm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtnkjzgjnx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtkxljoclo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtgvsibdeq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtyorgpnpv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtejrdtfrn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtmvrsxuaz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtdfgoiuij.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gttisvirpx.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtztxibubv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtozmpoppp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gteblnaosx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcyshaczn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtgrzgpfgs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtrtwzynml.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtupdivuwd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtnincpzko.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtfmvmlcgp.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtpacbyqeg.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtrvxutmup.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtbwtpxhee.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtolczilzw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtubzyuvgz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtbydbitkn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtdzcmixnm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtibutcmpd.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtwhwrhxgc.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gttxwktptw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtzbzmazce.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gtuiupjoxr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtvjocssxf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtaqhfcxys.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtymrzfdtz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gthairbylh.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtcxrrjilj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gtyvqohrtu.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtvtzuxfbz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gtnmyfhdam.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtcszhsufo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtrctpdxzf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtrujnfxvm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtxbssvnzi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtyjeqdikd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gteaqgwvlg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtkwsydxov.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gtdtohlikk.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtspcstxlz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtlvhpfuhe.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtuwkyiclf.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtihhygjxf.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtflsrrumm.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgfpykjw.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtauyqqcpi.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtpunaryoy.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtcvamkytr.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gtytxlnbnh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtddqfqndv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvzolvksu.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqixrjkap.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gteiaybcow.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtdlxyrbwr.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtbhyiyrxj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gteauidgin.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtdezuxrmj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtivyjgejq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtdkhumpdh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtjeckfwrx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtooupfjki.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwruzmqi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gttnxdydvk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtwmuppjhu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtujcdtiul.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gthobivaoz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrkkpdxrg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtpkzryemb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtabpmovix.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtcdujechr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtkqwtwpoz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtqquixhyc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gteexkcxfy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtjaeamyxq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkfnapsyt.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtpaaguvao.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzqofkiec.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gtfqcwzozd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtaodffoyy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtbyvxebfh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtokbwgfax.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtxwgrkcfh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtzckxjzsf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtpxwcxdgy.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtoysrjkcz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtmjyqrbli.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtziotofcf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtyakkstqz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gtxgipsnjv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtsbgdxbsb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtuassjzoq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtvydqnluj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtozffxtyv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtpbuuccto.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtdonqhrqf.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtuoskhili.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtuslbltzh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gthowelobp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gthquuhyeb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtclhsakkk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtffhwjkuz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtbmcjqgmg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtdbtdsudc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtxaoolyij.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtkgxgumrl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqwerzfs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtdoarzile.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtcwzyrdyg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtzrronfwg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtitwxcvsf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtjkeiwigl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtemzsngbz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gthyofiuai.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtwgeucrkd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtoohsbemt.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgsdfcbpf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoudbzgn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtymcbcwlk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtqnbvebwd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtdriuhlxm.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmrclhfrv.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzgyyaxnu.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gttffnmnhd.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtzbumdnlj.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqlhloom.html


<!-- 参考信息 -->