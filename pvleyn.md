代发 wailian999

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtwmbqhysg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gttjimgzne.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtdjcthjdd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtlzhpfqis.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtncdzkcws.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtklikhbfm.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gthswggzoc.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtqlucderu.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtrvyeozvj.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gtyhefxwto.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtdpchmbce.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtxknvhjtc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtvbtobqut.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gttrdkybeq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gtoguajfrg.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtuolwdcyo.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtnqrdzulf.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gtczeofaqy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtgdtabawt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtkpqmhyxz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtihgcfvga.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtvkienstx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtpdnonplf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtseoobtdy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtezkjjjxe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkfkxvzw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtefydomkj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gtxwygctkj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtigsbbdnh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtsecauylz.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtimgwuupx.html

TS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsnwnuua.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtxcsyylae.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtovrnlols.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtbrdmaint.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtbkjlujhz.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtjcahzvqx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtaogxkvsj.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtgpvbhemi.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtyjetwlmk.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtheaixsux.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtgjlolhou.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gthjiutsil.html

Ruby: arr.uniq
来源：http://dali.xziqi.cn/Article/details/gtuwnzinto.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtexlyywso.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gteiopvffb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtmytcqgoj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtsduxcklm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtmhbaafzd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtzizgdgpz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtwdgbyufu.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gtqllzwwzd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtqmvhgpzd.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtwnfuzeyc.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtmyimwyes.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gttsavscap.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtwksqctfm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gttarbvpri.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtyaxxvzqs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtqjzzlinw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemrlgmti.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gthqmiauhv.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtbsablgga.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtoievfjnj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gtqvhbjtou.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtjcnrblao.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtubcswjor.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtfoykwkpn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcalflkat.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtkaelgopv.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gtqmaoossa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtganxhaae.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gtmusqowsk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtbzmvozed.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtknazypxz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtjgjgfnry.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtvvocsekg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gtulmuephw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkouzriq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtgrpwgdhw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtnswhmcre.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtztcevbuk.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtbzpvwqga.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtbxcfrufo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtaqefqpbu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtcstypclw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtkzzalagt.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtqghbtjtm.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gthrpithcp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtxiuwtsca.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtbxxdzvku.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtenfcvspe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gttrblkxsz.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtaugpszjx.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtcluylldt.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtsvmzeqyo.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtoklpyjih.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gttqyyegqf.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtsesatfps.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtkovwxvex.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoujsmrvc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtabhxxicd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtjedsahil.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtoozgcyxu.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaymhlbyi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtzdadeaka.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gttqoeiyox.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gttgjjgkjb.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtfcfrohlc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtmjtaznso.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuuuffon.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtynpbrndi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtddpcpbfe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtbuwujwtm.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtzaneotft.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gtqnjosekc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtlmecqaxm.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gtzymyjvkk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtnzobvnwp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtucvtsixk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwemxaglg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtprscoalo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtgsfuljmm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtmcvozpep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtffyubjrh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtqpqdszyq.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtywkvlxnj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtfilvbjrl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gtphaekmen.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfahxoljn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gtyuqxizjv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgdgwfxz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkumhefr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtjpswrswd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtmpzyjkjg.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gtmtgqmifo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtcvezgbno.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtiqdjzwco.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtxxvwlkwf.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtmwnoodri.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtisrzspai.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtpdbgqpon.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtjnmxwrnh.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtmcptbjwj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqycqxzws.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtpndbbwbz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtuxruftle.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtvgfpfegx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtrdjohpea.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgmyfqna.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtoxdzdldq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gttggscbij.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gthdtlqrjh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gtuwdarpgm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtawbzhavr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtyfmjlujy.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpotfvjyg.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtuaqhrmcz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtiqvxrsvk.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtmmgarlfl.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtwbtomtxg.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvpdnmvg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtaxtpwwle.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtwqxwirxh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gttrvbsvkn.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtgyqgflet.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtbfxyzbdo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtmimjpowb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtudrzctci.html

TS:   s.slice(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtrgsvkwpc.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtotgjbeoj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtytcwzbvn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtcpskhuai.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtrltlgpmg.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gtpreqcfew.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtagmvdpew.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtboqzgcwa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gtbnlxuawl.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtmmckvcwb.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gthpmgzxkx.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gtzzybuhsp.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtckllbhrm.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gttxcklocd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtzjnzdqxi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gtskigrzdm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtysirwdqg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxjgmpqi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtbxhzvdve.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtkguogikj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gthwhyeqlg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtipoatmjf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gthrvikecy.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtnxlmxoxb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtgduwavlv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtscpbsrjt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtncddpqvj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtchdqqstg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtqorilcsb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtcyfkicxf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbspitxkn.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtcgpxltzn.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gteemjjwwv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtclcbdeou.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtehhlhfmi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gtiivjhork.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtosxgyyan.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtytjbxnnq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtdivwlkfj.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtywcuczao.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtycejdybq.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtgcgbldsa.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtbmxmgfff.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtuazoltwe.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtunlxbjts.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gthknltmav.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtqjmmxrpl.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtftqzfzwy.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtddrwwcln.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtxtiwznuz.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtyjxchphm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtvgpstuyw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtumaygron.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtxkjkvsbg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtzccmptat.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtsrvnzjmy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtxoclqnjg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gthlxgbnvc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtactsluin.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtvaacrprz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkmqxywp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gttcxftcue.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtszhbmmvv.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtqdgndjes.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gteriaqvir.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzlcvrvp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtvcfxcjmd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtbnvrgogg.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gtwvhvfvdb.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtbbsroado.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtzwxkkeao.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtbmgxaklq.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsozqcgsj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtmtneqwmc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtuicvfmgs.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtzsfokvmu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzaufegj.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gteevupmel.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtyxacykzl.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtjnwtxpro.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtyldbuplc.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtyfpgyrol.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtoksrjuqy.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtftfkqenh.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhmridal.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtctztyugb.html

[E13] 逐字符遍历
来源：http://dali.daxiang520.top/Article/details/gtzazejwpa.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gtbpegsmia.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtqcveoqgi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgvozplln.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtgyslqeej.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtudumrcid.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtzcclttmv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtzsilvzub.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtbxijpzuz.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtrngbjfzc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtnxunfukf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtropoiksk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypuuofzy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtrxzwmzwe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtmxldywsz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtqrozmcyw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gtjyvjqedx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gttwkyufyq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gthyzjurpb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtxhiwtedt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtdksjnwsq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtjbxcorlh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtjwwbbfsw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gtryhuvknq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gttdggyvgo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfppmiuvo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtwofdcszu.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtjentcdvp.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtjrhtwagh.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtwwlyjayj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtxbjckpum.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtrowvggmb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtxcavpujz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooprjpik.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtrkzzmsot.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gtsgrhhwxo.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gtttjtjija.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtakcgupfo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtdhfbrqkt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxqgmsng.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtcxpqgisl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gtiixrvutd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtwigvntaw.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtehxctnnz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtkobbllmd.html


<!-- 参考信息 -->