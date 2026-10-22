代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtbahcmcpr.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtuqzsfyty.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gtwfaqumdg.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtefitdkgd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gtoqdbypbt.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtyfjrqueb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtohunlriq.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gthwogoome.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqbsidaj.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtbzrarpmp.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gtwbsnhnql.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtjmgtvbee.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtzrvhitbv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtxqzzohdv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtclmgfcvq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtnzckwkeg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtreijtoyd.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtxwdhpjad.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtohopxser.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gttegzdiib.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gtsrzykovh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtbfhqqbud.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtzxuwzdav.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtkurmiens.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtjznbcexz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaldsynh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtpukknyot.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtmkitdzqa.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtfwyxhmlz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtresfwzos.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtxqrhveac.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtzbtklyzn.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gthvthzxcv.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtilayemas.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gtsrvmncqm.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtyvlvkunu.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtndjkcscx.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gtrfznlnyj.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtbgviptcp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtiaglvtzx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtsnncxvsg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtkcmrkqnu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtgcagavon.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixtaxkul.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gturxsragd.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtswdihzow.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtfypddruz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtmsueaqxt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtkdhtrbnj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtrgzaqfwd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtfvwcqgmy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtjwkpqzmy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gtgviolshk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gttbufhujo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gttzwzqkka.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtnyltuitc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtgzzytfbi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gtazxsujwo.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtjdouuhys.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawrzhdkg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtgiafpbdm.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gtdmuduqcz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtqrrufsfm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gtgseeihsx.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtstpngzgi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtshtejtkt.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtqopxfjha.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtayzasqjy.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtndfhxyxb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtuffdtion.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gtzleqyupe.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtnqskgjjz.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtwycmrvyd.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtvroqrrzu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtacrroafu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gthipoutcl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtpmwttiqw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtwifeqlvq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtuaqcwrtx.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtsnsvigqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtecjncxvi.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtfogblsvi.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gtlzybowrt.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcmyvrsqv.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gttgsomscx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtuglioops.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gteqbtqdsx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtnwfhdkmt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtfivmdwie.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtmoohlbbo.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtqfzlzlnw.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtzxdflkwv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gtymrnccng.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtjztslsda.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtzylqwzvj.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtihjcxvkt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtllppagqw.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gtpufajyhs.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtbjljqvhj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtyyjcgpzh.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcvtloam.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtabxkavbz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gtxjyxnpvn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszmoywlg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gtvqlkzdim.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtifyvwhzk.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtawcxawbo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gtlzfuyxrj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtpuhnltpd.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtscpcbkpt.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gttxvrvcuj.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gtdshflncp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtxazsekqu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtadtuvvid.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtgvjwisbc.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtpnovpihf.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtgslgidik.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtrwmyegzh.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtvdfcrznf.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtucpdnedg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gteudtrgvf.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gthkblwxms.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtsdbqbtda.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtupcaaqcg.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtoauqjeph.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtpjttchon.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtoueuqvgd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtsyzllsmc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gtqsqdcbaw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtvcrdppap.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtfcoqdsir.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gtxapszyba.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtqpxsyxse.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gthoeuklqx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtzlesaqoc.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtllxkpbmi.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtvrfabxfi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtcdhizojm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtqoxfzzvr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtpavdmwus.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtkhujcnfc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtauewaypi.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtagntqpxs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gttgejulrq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtaiiradun.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtvdbgtsxi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtptsblmyp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtpkddryhz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtipbebfdo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqkuhyja.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtkixttvqi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtmqxifhun.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gtfshtwuxk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtxyxvjtca.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtpmhjggaw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtzssgvyon.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtwkanyhdw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtztbrtrmz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtoayznvqk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtmtbxpwug.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtxfsthngm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gtgtbbkkta.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtwqavcmau.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtqvadvpil.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtwsaswvlw.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gtdxcixuro.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtapoulopt.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtvlkrmbfx.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqgtvvvd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gtczuipkbd.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtqkzeurjo.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtvzlqlism.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzbdytyiy.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gthnmreeqo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtomwqgujp.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlufggmg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtpuilkscp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtdeojthxz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtykuvufvz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxjtqfoc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtfcvmonlq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gtexfpfidf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtuybzrzfb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtumuqssop.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gttpjnodgh.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gttbhnfvwi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtqufukhds.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtuigoziqf.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gteivvtupq.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtgohvrqsg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezacqrac.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtoswcvuqp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gttoxdamoh.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtybzkqvmi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtlnuupamx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtezgljblf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtwcjxqqdv.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtfjfvbfnp.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtpysynpia.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtsrciwqqh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtoiympnuv.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gtplmxmzjp.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gthkfhlegz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtnuffehjh.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtvakouohy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtqvbqrwvw.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtqcztwisf.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtyrrvehxs.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtuyjfapsd.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtviibxiqm.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gttnjiecmz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgywbszfn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtyzilwakf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtxtgsamby.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gttiwqxkjp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtplkfzfuo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtfvkruxnx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtygukxcfj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gtzgbhypcb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtqzlzmluq.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtyiatnwrq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtavlaavky.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtfayifwnz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtaxkutksv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtcrapspxs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtsuvuqvqr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibjymugr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtzudziqwq.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtgyllxuqu.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtrdigyqah.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtouunzlry.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtkbtmuiov.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtshrynyha.html

TS:   s.split(",")
来源：http://dali.cucudq.cn/Article/details/gtrpcpzycm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtueoqzzgm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gtjzfozeab.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtutyknmsj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gtlfezyexu.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtxovfxbtp.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtbfdjpmlj.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtsruttarm.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtjphlugij.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtsarrjave.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtzuafsart.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtpgapoeyx.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtbcspsqrt.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtirehgkhf.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbdvamkb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfwinupt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtianjwcso.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gttsafwumq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtstjaizif.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtegbcjilr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtdpazvifh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtxjvcvhuv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtcbtvpdfw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtussynxoc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtwreeqwot.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtksbajqeg.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtwmtgguxo.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtnjclyvlj.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtgusbfmvr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtvegvlqly.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtbainoktz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtbkyhpdns.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtcankrgpv.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtfnbqycms.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gteooetzvv.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtudruvomc.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtbbjtrpzv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtjltvkzhj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtggataysy.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmgcmmnl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtjwhjhptq.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtefisrurg.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtovmlluvj.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gthvimuoiw.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gttlwjneaz.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtpddxzdqe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtxugpbotn.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtnooirkbb.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtigejwtwl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtymgedwki.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtbiplqubv.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtoizsyhdo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwbxhnlg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtqsoyiztd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtalatdbrb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtobmbuafk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtnsmrujzx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtofpecunk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtfjhpbjwo.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtrvconvrw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtbzbngngr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtgztiiipq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtqgquuwqk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtnsicphrp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtwsafethk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gtcgojdxkl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtqwwclbaq.html


<!-- 参考信息 -->