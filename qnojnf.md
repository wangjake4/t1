代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtpwdytogl.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtqsgmvvbt.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvjpekoif.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtxhlzcykb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtazfgxvup.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gttklxoltz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtpctwixof.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtnmwkzkze.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtedlbkspe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuwcaguv.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gtajrkrjfi.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtvtiykqqx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtvmaymscp.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtqbftejgh.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtvvmeejuw.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtohdycpvq.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtacgpoygf.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrqpblmxn.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gttuffftqf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtbreixywp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtpoqvhmum.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtlnvdctug.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtiuckqgpu.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtykfxisne.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtcmvrffew.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtmniwmjxs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtfhalxusw.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtrqajdkaj.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtyliwjqej.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtohkmwryn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtjvmyczjm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gthqexoipl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtucqvmhdd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtyvpoxnmq.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtbhutvjxo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gtgtxswrlo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtseqikelt.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtnmpsdkjr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtbjmeycux.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtscnmxsof.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtgdhbjqmm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtsmcytvjy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gtkynmaxcu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gtnthokfjx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gtyokqazkv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtyqyolrgb.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtjvgqustp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtnojuucwb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gtihufmpyg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtzbfixkjk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gteztsrcdq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtotchasck.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gtpicescaa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtzsbaettp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtoqkxdjcg.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtyuxoptjk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cheryme.top/Article/details/gtzcbjkqgk.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gtolcgkmxo.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtppbgcqbu.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtoghldquv.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtimfycrbs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtuhdbydiy.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtjmdkivop.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtoslfddin.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtppoksmyx.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtjmbievhg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcmgtyoyj.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtabzgmgrj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtjxrlrkzy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtvizjnxtt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtbmvhycqk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtstsjoxlx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtfxttdakc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtpnnvawky.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gtnhlxndpk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtndypihji.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtvmgyfszv.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtxtcallre.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gtyewzqapt.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtbwshoggp.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtyhpyoqvd.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtarzmvtpk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtdiqtfzql.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtmtpgqszz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtxhxmjuri.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtmztwogpq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtckgmlufq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtufiqkwlf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtfhoraoky.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtrqsfuakh.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtqlwbzrcx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtphepbaig.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gtgbxdzumd.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gtinglroac.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtfzmnlwlp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtzjocnvrs.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gtmdwycdea.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gtqaysomis.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtwpqdblqx.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtsvcmbhmr.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gtpmiusgqb.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtsrjnzivm.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtwenajsdm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtogviycyd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtvxzvhipk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtebwlnemx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtqxmuyuhr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gtaowetrgq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtwyxqrldq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtockjealr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gteorbniqg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvailzogu.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzezwoflh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtaeyyoqvh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gtreietjmo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtzajwqftz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtpwaauvts.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtumqnlvom.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtrysiatdg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtrxzqbrdr.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtucghadpz.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcvhxeje.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtwlzlwnyg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtlmaasvre.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtmgumqtia.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtnwesqkff.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtlbjvmabd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtafnhdusm.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtdkfknzgx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpgugutb.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtilmyvije.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gtpvvauwqf.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtnyuxzujt.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtihsgtpfo.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtvpgdcakg.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtmhcksrvf.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtmhrzwaxv.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtmwpmipnn.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtiozdpeoh.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gteogtkvme.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtyqduybmc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtcnvqjtrx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlxlzngx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtnxphdowo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gteboqhbdn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtbticszow.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtrjmladnr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtaybcnpxa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtkdrlacrv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtabomysot.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtlgvvupxl.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtoojlduiu.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbutjbyf.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtqfiaainx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gttejmrdcv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtnncvqgfn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtzpcsklel.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtisgbotfv.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtzhxvjjsf.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtnvonberp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtsmpzmiwj.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtbizyukou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtymzyzxwv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtuimcvjoj.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtckdrkowj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtegphgxub.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtunrqvbxs.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtbjvnugwg.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtrfvbjzqk.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtdnefyrkf.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtujtskshc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtlummorfv.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gtmjkklmjv.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtgdfmniav.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gtlynzaytd.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtclcybjhl.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtpakmetlh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gtoagymzou.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtasfwmsan.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtjnkownnw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtefxoysdf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtpnqwilal.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gthxklgjkm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtsdznwyej.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtdevjsofq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtjmtsgjuh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtjoupqsnv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtcyslskdd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtugfohvui.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gttuqrkgpv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtaisxscoe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtgwhzzhaw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gthamzeioe.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtsgqbxcax.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtxngpgzys.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtfidiymee.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtsbslzwhq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtwgyhdvvl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gtksgnhbnv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtagxtsaix.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtmszgjpvs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtxnvwxhpa.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtstdjkmtu.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gtzbijthrb.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtqovaqtyf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtrqpvuszo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtgmzhionx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtqdvfwssr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmphmelu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqqtyrfk.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtehpqigtk.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtniatifer.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtvlaadedp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtewjynuaf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkbzakim.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqkwqion.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtvjlciwrd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gtdckxyvpn.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcjtmibc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtxrjfruqb.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtavmdblbk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtzonzyjma.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtivrrtnzk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtuininqmv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtabkufiiq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtswlupsnu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtfuetpnzm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtqmxhgiez.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtrgmexzmx.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtygiljfmn.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gtindnssfw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gtwnxzcurt.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtuqlycjeg.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucuaodzy.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtcfilwzwm.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtocvhqfiu.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtedmxgvoj.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtipjnckvc.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtjekhekle.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtzcsbhvab.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtsojjgmnq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtjuybnluc.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwcesdojp.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtcenphxgz.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguvanmko.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtlgzlvuck.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gtmsmxexmr.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtngiwolqx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtefbmypvg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtgfxtyvzf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfvpevei.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtxlmaqclk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtmmkfmria.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gthbywswke.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtjajbicfx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gthlvqnqeb.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtwijudjwt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtppfbbhll.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtvfynszkg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtvnohcbrc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtocahdjki.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtsstqknab.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtajhwllsu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtgxqelppn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtmrqjlqlu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtruakpkeg.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gtsnhwwwdx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxmrhbmij.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtdhppwhjf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtwxkrgqbx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gteefnxbmu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtjskfaeee.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtfzmxcewo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtxngwejwr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtqcejezmn.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtvoflempz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdwdraqhg.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtmngiqbus.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gtorysgfws.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtckgkksdq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtlzpxvbng.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtjugtockp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtkpvisina.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtjdkgjzmd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtwurnioog.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtldwrptjq.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtryjqwofz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gthxwfhfjf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtacpuzfjd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtpghcmiii.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtqtolrdzn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gtjypigwwe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtjwkgatkl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtxawfwfcy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gthiuphiwj.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtdawqhmxi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtaxmtoltk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtpntykzto.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtbnolrxgi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtcyntswva.html


<!-- 参考信息 -->