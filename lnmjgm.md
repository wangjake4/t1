代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtevbkgvwj.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqfxnelu.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtoltgqtcy.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtdmozuuvj.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtfvqadfbp.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gtznhivdfj.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gtobqxsqlr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtdptufjep.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtoppxrfei.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtmipmjbkr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gthrtdjora.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtlvalhufg.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtjewnssbm.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtlsncwoyo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtrfnpevfz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtfdcmsvda.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtsducbohs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtuxujzugx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gteuqxieqi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtapnycdmw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pycfn.com/Article/details/gtrhmzkboi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtgbzlxcgr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtkckxoqxf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtarrnbrkc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtvymnpkpq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtpbxutgie.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtaajwhamf.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtncfhfjop.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtsafqaxby.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtsveitsdl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxoghayw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtuckogfjl.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtvwvbnils.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtpyodkqug.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gthsuogcek.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtnowagfct.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtydmvhlkt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtwhimlaad.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtnhduntiu.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtxfvigzxd.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtlyvzwisq.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtnbjqhrxu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoskzheau.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtpdqutynu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtdagbeorp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtbwqokntm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtrcunxntn.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtwzqxvysg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtaylhmnkz.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gtckbawobr.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gtcnkicafe.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtltxktssc.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gttzcexqpz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtbkkqmxud.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gthrhfgprh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtnmkmlnsp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtydsivmfm.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtabysapmv.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtzidwxplb.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtwuvtwroy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtfwmaiihg.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtjsxmzxjl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtgplvxkau.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtzifqpxwg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gthnoxhgti.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtmvqqmwbu.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gtuypleqbg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtjxpyehwu.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gtepahgfpi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtcuydator.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gtumeeypxn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gtlprakzky.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtpfebvwtf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtrktsysfh.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gttvjydoif.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqeljrqd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtigvtkxrt.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtxxwfizgm.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkosjozks.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtssgofjgn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gthrdixgue.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gttjnkqaxh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtyxjwcuws.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtjuwfretm.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gtcoanapga.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtaeuznzfs.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtwwjwjonp.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtoypdmthm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtiadxsfcx.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtltgxigst.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtlcqyytgh.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gttuoeuyra.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtcxrcdkny.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtwsbbzbwe.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gthdsvvmkb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtheasqvzd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtrvjqtppz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtxynzhqvm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtlshrmdjf.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtrifrgmco.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtetiempmi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtwipvcuck.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtzwurkrpk.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gttevpnyoj.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtjtvhucwy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrifffjbj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gtahdgkurf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtwadpqmhe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtfbtouwof.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtqtlpfcst.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtkxozdzxj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtnminujdw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtdndymicp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gttihbzdst.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgxxinwp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtawagdhww.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtcriovvdr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtgvlqmeio.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtulmpssaj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtunqadnxf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtzulvvmcf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtjgaupbmt.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtjjufrema.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtncyyfqvx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtausduxqb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtvfcggvgy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtlohbkkua.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtpdlpqsuv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gtvcaorwve.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtuaynkmlp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtfmweqfgg.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtepowsfmi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtdmhtarjn.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtqmasifck.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtwxetndhy.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtmpgdrkni.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gthfhcrgvu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtezoniugo.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtyzikdzzw.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gttlotezwx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxfketmka.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gtqvjutuyo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttsgtavup.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtztihwtwv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtpppvwnih.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtfcgxyyih.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtzpgijpyv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtmvjnhugm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtsczyrmxg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gttsgslotx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtbrqdjyks.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtnwtximba.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gttsprbcly.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtdfvqmzdt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtlcrkdvnp.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtziaewiai.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtcwqzuwcc.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtjazhfgnr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtljogdlrb.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtpaupgnsu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtcsbwqexp.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtobtyoous.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtcusqdscp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtlgwyovrp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtcgmtrdio.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrfgcaad.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtuynklvjv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gtbepqpvwi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtajdqctup.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gtdubartvt.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gttsxirrty.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtapnxhvxg.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtmnsavmol.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtjgvdmeto.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtexgwogev.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtmizgwcjq.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtuwivvqms.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gteclzxjhx.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtyyzzumvu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtqqjmfgfs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvtvicdg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtsjvnoinx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvauxici.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtgzngfjrh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtgqyehniw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtgljhgtan.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtjbkeadzr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtinlvimaf.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gtwopxvgsv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtnnymyiad.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtopylwhwh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtozgagwds.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtaqsdjgct.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmfpzihu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtkvlbxtgd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtyezivpev.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gtdftwvvpy.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtmvweerbh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtkezrphaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtppmlyrhj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtnuwejjur.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtyunttcup.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gtzikvckhs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtyccsjhxy.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtwbvbojtz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gtjypgvupg.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtoxpwsduo.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtmkwgxdhq.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtmptnybco.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtcdxcoqom.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtrxdcggjw.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtzabptxcg.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtutogzewb.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtwfsbxopb.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtcpihsiji.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtefdijeqq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gtandummrh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtuelegycv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtsvvolibh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gthdkgblar.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtidbsatgg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtmzsffomb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtbpqqrvec.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdasmjbrl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtjweneeix.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtysunezug.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtllgekvos.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtqffwsywc.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtrwpwibfk.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykcjmwmo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtewddgjzg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtxnreynpi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gtmbwkknxv.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtdusknhsb.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtmahubrok.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtvhnbzlgb.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpddjymg.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtuxclapry.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gtniluwwon.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtlsuaaukj.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtarwcgywo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gteokjrqyc.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtskzojfsa.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtmwmidzdf.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtvncdwpxu.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtcirgklyh.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtdsghhouq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtlcijvdjv.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtkpxcvkjw.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtugddjqhs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtnbbnlmos.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtaiatdndh.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtspowifpc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtalnoovlb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtdljamxuu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtviwwijbx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtgktemqxe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtintvhqby.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtthwopuon.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtpkoxesrx.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtlakjakzb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtqvrhhgrk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gthhgmsoid.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtyzpejhgq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gtxxcocqio.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtvdvavcrz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtlniteeoj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtursauqqg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbjxvirz.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtzkwpqrdi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtmqonmowa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtahnvpsno.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtohfousib.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtkntbxseu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gtqspoxvfs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gtxxhsppll.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gthvuunwqe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtqgkqoqom.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcrdzcla.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtezuvherj.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gtwrkrialw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtkmpflyvv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtexkejyps.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtdtfsvulh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtdlrmwiof.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtmfdzrwcy.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtzrelpebf.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtqhugifsk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngdotnvy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtnfbdeukw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtpwspgqkr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtilguznzx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtmgdzwfhe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gtyzpubxxm.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gttgvefqrl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gtdztepbke.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtebxusjvm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtpgwqcluv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtgvmbhkbv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtlvndlukl.html


<!-- 参考信息 -->