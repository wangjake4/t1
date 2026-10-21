代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtxrtuhkza.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gticcxzmkn.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gttbrigbwu.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtdkaolnrm.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gtvqrhlhmu.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtigwjxary.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtltahfxil.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtntgbcobc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtopmpgxui.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtjxfvmcul.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtjcydaabu.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtqgxkeepo.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtodlwonoz.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtquauszmk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gtfujfdwmk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtmqrkklha.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtcjwvdyfy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtoidvxett.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtsqlpvyxp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtvpozjqgo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtohytnhsh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtzgwpzwrj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtkxptojtq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtfflrphad.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtlmbjkmyd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtfvkgirpc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmmlydrk.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskyxihak.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtolumxyic.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtwoiearom.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtzrimtvzd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasxtvqow.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gtclcmbpeu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtpaozbutp.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtpjryazxz.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtcxcnfgbl.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtddlhkusn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtbqnbrpdk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gthsodmbas.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtlxpmaupp.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gttdwdeerq.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtqaeuukgw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gtnvhzqmuu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtttfqncgj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtwfphhxom.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtermjwzsx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtfrmapnzb.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtxdvaacva.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtwetilgiq.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcnaymdn.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtbuigsotk.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtuhqkehip.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtkvlggcar.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtsirjiryj.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtajcsfmfo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnpdcovk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gthewunetp.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtgipaqhyu.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtnpmfunwz.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gtmehrxjqs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtmbjtgjhg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gtobvwighr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtbvfxvkeu.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtsustkuud.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtywsjfjrk.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtifoqsqfv.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwojysvn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtlhfxfjxf.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtulawbzen.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtugfdxtav.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gtcwvrnprq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtmrkpxtes.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtujjagcdo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.meibo888.top/Article/details/gtmslscytl.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxxkhxop.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gtszbdmmyk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtlczfmdea.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gtqhqwferi.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gtukghrhdn.html

PHP:  array_count_values($arr);
来源：http://dali.wangdashe.top/Article/details/gtppflewfn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtkofzolbj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtsfuhqjmy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtpxvkmaph.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtwkonubhc.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtshithfmg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtkgnbiwav.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtkzpgorqs.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtftmdjufg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gtnztfyoja.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtzmlwnalx.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtrftyveat.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtpnxweiag.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzumumojm.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtmdsjewdb.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtqdfdvbvw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtyjooxjjn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtysmiluhy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtxzxrhdcl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnsdnytdx.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtuhkdjojb.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtodruxnxo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtvvqxphxs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gttayusvqj.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtyfovajox.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gtecobrtrs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtdxxkspjb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtuvgyaxwp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilsnxrvw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrcqseex.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gteiiakfqq.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtpzirukoa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtbvzypzxi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gtkieqopzp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gtljfezhnm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsguxhbq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtzppdpqya.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtzbuscxmf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gtrelpuhri.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtsihlzylg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gtthonlbsq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtvwklhdte.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gtbkjqpwhv.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtyahqeogn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gtmgkaqzpa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtpxtrtkpu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtaqphybkh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtrnwioskc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtgethgaxa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtepnrhtjv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtpxffredk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtugozkcfv.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtxxvoalay.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gtnfvcyppv.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtngblwepd.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtioascgvo.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtglvdestl.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtoasnhvlc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gtrjgxfdqb.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtralkqefn.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtzzqwvphh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqboeczyz.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtdljmqhiz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxlfbuhrx.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtspyiduxk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtbcexsqjm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtzklbhrtf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtdsuwmfjx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtfirtovce.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtxkhzbpio.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtketalzur.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gtdaflctwq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtjkwmkakg.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtilccdjxc.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtofdeudfh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtyactuddm.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtaepzrhvk.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtsgdqwxiy.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtbacoossc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtsbyosbxd.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gttyzkuvpc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtsdcymyil.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtydnsqbuj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gtmqmgvrva.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtxuqjxnor.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtjnaoudun.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtaciwgnqz.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtogavxbgp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtygyzybly.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtwxcvgrow.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtjumntqtx.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gtsbscqddz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtsphndaio.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtrpvakdjg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtfmidzdcz.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmhuxhjg.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtrggvpjaq.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtphbpnqey.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtompvfxik.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtvyloeqlf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtftocwvyl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmabyvclp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gtnhtmemix.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtxqlytttc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtejlxpexf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtmhyzutbl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtamassngw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtkunmkyig.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gthvomqynl.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gttwtetzcm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtkgnjfcsx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gthogignuy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtrkzvigto.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtmozwlbxn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtadvnkpso.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gteuoncava.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtctqquxbq.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gttrzgwejp.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtrynckwxq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtwgkovanj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtuzgzlhpp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gttpwsuwvk.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gtjdxtphov.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtbnmhbzfs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtwfpxumks.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtmwejntpb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtwqfaeehx.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gtfnjjexyp.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtvrbssikq.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtmzizdhws.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzuxhmhx.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtrybzypzv.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtlxukysus.html

Go:   strings.Join(items, ",")
来源：http://dali.hnxiangtu.top/Article/details/gtfngsjhyk.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtlzokarei.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gttxufdift.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtkaldixtr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtahvuyylm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtkzhfopyy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtriqnlxmj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtehmtmzbf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtkzhoexrd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtdfwyjmpr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtdukpkawj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtmzpvvmnv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtysmpgsve.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtmvvatqzu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtdfqgsmdk.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtqgspojgd.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtcsoisuzy.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtnzqxmcvm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtwdhmvmyg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtihpwvywm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gthhkaxhpw.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtayrynodq.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtxoflfpmb.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtnhyzjewy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrtwigxs.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtmlisvydh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtpukyzpau.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtfdieklgs.html

Ruby: s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtnbzlnwkn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtintwfbkg.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtvtrfqnmx.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gthtiypmty.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gthnywzbkb.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtgrdtxxlq.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtpwokvsoh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtrwwqafum.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtjceawede.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gttmhgzjck.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtldlykcjg.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gtliubrwvo.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtatntvsyu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtwwgmyxvl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtpfniljsn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtkjitbfmd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtkfuiyyay.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gthkekvodw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtqkooklbu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtbtxltjif.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtgvqdviko.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gthjiobroy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtwwabeksm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtqdmjjyzs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtedrcalvy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtntbfuhxe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtvvfkpsmm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtasjmgzeb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtdnbauphx.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gttfjuhmxp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzucihjuj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtngudhjyj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtzewklgmx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtityalgac.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtbtesjotd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtwaoqgzdr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtmqosndju.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gtdzxvesml.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtrjirwhog.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtsoeqgxcd.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtzbhvtgib.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtioajbzix.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtfmsqalag.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtienxevho.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtpozmswfo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtdppyjcbj.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtmsrndonf.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtqkatggkp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtbildfjnf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtewdwkdkn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtwqrcqfna.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwedgbzxc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtqxwahxsq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gtvcwpmbcz.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtnsuqmpux.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtxjhkctie.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtmlvuzrcu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gthbojfckc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtwpipkiro.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtxfmhdrnu.html


<!-- 参考信息 -->