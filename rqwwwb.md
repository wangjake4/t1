代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtcnprlkvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtxvqovcyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtyznaycgf.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtyryteofi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtdobwsqds.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gttnxkufgv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtbimhyvrn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtdsphgfyd.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtbmrdqqlt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtauwfacuw.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtbmdafdth.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtcjhvdfaj.html

TS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gthgaqmyhq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtorzhkimh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtnhioiitg.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtpmhfnyyp.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtbnhcmszz.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtipjyjusx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtigmfnmvr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtuqzsslla.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtecwuskfa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtpxqwmkzc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtlnwtbsvn.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtjfhhjzbt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtwetqobdh.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtbsikbjby.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtubqlwwrk.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtvdynklre.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtxoahdywl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtruplkgjj.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtzrsatupu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtfxzgyujm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtpgmsaddw.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtjyqmwhck.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtpkrjuidp.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gtaojhmmki.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtedolbdbf.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtimckwfvk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtxvbirjtu.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtgoelkynb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsjjjtjp.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gttdiqjzms.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtsxaetcqn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtabcxlhmy.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturdklhgv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvxaippoq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gtuovoefbn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtpwibibdt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtxpdvebzw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtgzpmbstt.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtvakuicxj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtjvibtdsa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtftedrgok.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtlmlteewq.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtlarikrdd.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtqjzfztpl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtpldqadvy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtwlopbcha.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtbzmpboui.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtiddzqzvx.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtcebmhsmm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtfbcdqguo.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtjwefjvfq.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtaeqawnda.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuugtdfgv.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtqihvrpkd.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtnburaewm.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gthzqaqvrl.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtkccigrbp.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtzrfngavb.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtkazmrasd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gtdqawfvak.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtgtgbhdla.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtiuisypon.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtqmsbiujj.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtmgubffga.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtfuyqcttv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtcdevecsv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikjfwoze.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gtbgsnfzir.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalgeizyr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtuamlbxeh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtpjdwzpbm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwghhuczp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtmryiexih.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtwuncabvu.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtejatkyqs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtvhegydgr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtiyvxfwox.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtdhpirjol.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gtyclftxqu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gtzuyntfjd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtvpyzpndk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gthdnffnim.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gtrujxmrzb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtfujdvadn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtucswskry.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtfybektqp.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtiypxzain.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtafdlgdzm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtfuhxfdfv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtapiwtvgp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gttpkpbxhg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtnfiyophg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtqhlzqaua.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtsmoxxbio.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtqtcvxjjv.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtizxinfim.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtqanzhbwi.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtofbxjdlg.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtnptiluka.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtupwtyqwc.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtggmtlxxf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtngxkmrmu.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtyefgpzao.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtqjshgfjh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgddngwjc.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtskzfydnd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbemxmpsj.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtxrvwrgji.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtpcgulzvw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtrylcywnz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtcuqgsqmh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtcfloojto.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtmhlqkzmu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbnwwhaky.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvvrshew.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtdgxhcwnk.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtnzhppazg.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtexfryxsk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtykziqqvu.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtlrckvbep.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gthrvrwddd.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtzqafoggr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtucaoecyn.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtqangslgb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtqwishcuc.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtsvqfdplk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtspoihcgw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtbncgfvbf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtzsroyqzm.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gttvbbtkyg.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtvnyzkbxr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtnbadqivb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtavuskkmk.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdcdiszmt.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtovxbqxih.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtatffadbp.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtknqaiiio.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtcgbuwtzt.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gthomjtvbz.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtrqqqbukr.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gtbidhzlhc.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtpweddeyy.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtkrmyzqwy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtejhoxdxw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtskwhlwus.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.svipenyu.cn/Article/details/gtlkfkfcja.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtfsuavrcg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtfwuqhksi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtyxsvioiv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtdcolksaj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gtiwrsnqzb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtwdkadtld.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtjvjpsuwy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gttqsranem.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtvzwbpgsq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtwkpvdaaa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtpidqrlcu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtwwluozwc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtfyyoylza.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtlabzmssk.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtnbyjvfny.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtxduhqcrz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shuidangran.top/Article/details/gtntwxxtfo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtdvtglwcd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtgxonbulg.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtfusxwkvo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtuhfwpnev.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtenecoldh.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gthhipjnrr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtltjqmgfo.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtatzglwzm.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtadurvyyd.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gteillzios.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtgzuwikzw.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtkhwqujdu.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtggaqohrx.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtozpwspgh.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtrjfcvemg.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtawzsgmyf.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtplxoiwxt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtwmqbaitd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtexjyfgav.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtlomgumvp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtghgmbgwc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezcrydrq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtjuahjowx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtyhxpdwij.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtizriovni.html

[E10] 左侧补零 / 定长填充
来源：http://dali.mhx1999.top/Article/details/gtibwcrzjk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtttjufzgr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtojkmysan.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gthribzqbe.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtzrgptrvh.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtgfgsxssp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtgztwwqud.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtfqyxypsk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtqelkleny.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtlqkhlycw.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtmfkwimaa.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtvvjxxqzl.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnwzdani.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtqhgoepkm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtjctmvqtk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtlhfpkuxp.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gtugpqhbad.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtsardpwvt.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtkxiramck.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtrojyydjr.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gthltqbmnd.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtjqobnily.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvntaqzip.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gthgsmleiw.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gttbpsosnx.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtljyxuuzz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtuvdtqlea.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtlmzszizm.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtzangilam.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gthweunqyg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtskvwdedo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtaeoannra.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzupnknpn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtdryqpehm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtnquupxke.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtaqgxuctd.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtvyjjlldr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtyfterbet.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtzuufaryf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gttdczaomu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkvnemlz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtebreoosp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtychbfzpf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtwpiyuwxm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaolonaq.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtqkvsyjma.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtpabhstcp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtcfuzwczm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbuylwslg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtfzclvntf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtlwxotcth.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtqcodcmcs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtmcdzutrt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gtuqndfsdi.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtgecffifg.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtlcaprhoc.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtifdvlmut.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gthekscmpv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtcapponzh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtwszybmcj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtjlgbhalr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtahcplvbn.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtsobksngh.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gtslmzvigj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtldtlhavp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtgpfspquc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtabjrsikk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtldqjnxqd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfptuoslu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtpjywgulk.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtsytfygbk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtbjiblnpm.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtxgxuouds.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtcqwmxhas.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtmtlgzmxi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtqmphwhyh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtzspouela.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtxxwdntvk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtyxqvrcgd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gtolmkjrbc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjzgqyxw.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtdxjgoqgj.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtegqvbvph.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtlrymqmzc.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtntbohjdl.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtmupsxjto.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtghcvsfpv.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gthzrhrgwm.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtzqiaygkq.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtmypwtrlg.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gttjhaqewf.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtcrslgmev.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gtzxfbgjmy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtvjwtxrdk.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtchwzesdv.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqovjqzlr.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtccxijdai.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysqqhcpt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtojfvhnni.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gthdqktlgj.html


<!-- 参考信息 -->