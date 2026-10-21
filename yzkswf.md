代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtuvzwoini.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtxnxbrxdk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtwpxdifcs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtgggscgbn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtwpsamabj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtlzxicmel.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtzrgkoiqj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtvtkekkzr.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gtqikxyasq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtcstflwct.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtsnhxvkvk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gtchhtedmv.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtnkcvezoc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtqnojhkzq.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxtmecja.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtoyjejouu.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtlryqramw.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtmjbcqqpm.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtpeysywge.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtyutkkako.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gthbgycslg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtjwkoftgb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtcumehjgm.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtkzwxhlcc.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtuywlktfc.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtlabvzirz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gtdhppbipq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtmblcxxxc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtzzefulbw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtqylkvejz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgoasjxjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtdexaejbb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtgytkqtam.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtjsmvnbqt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtvqnjxwks.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtmqvmwkga.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtiwvtkivp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtqnsabowp.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtsevllusy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtszoubcmf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtrxjasdwp.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtpoyqfpla.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtgklfnrwd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtxuwczevf.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdmfftgb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtbychsjvy.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtodtdywms.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtwkceqrzq.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxqhzkmq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gthzjwesdy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtzualaora.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtrdhsmhpt.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtvtfleklm.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gtsdtaykcw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtqrivggzx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtujjajvjo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtgbqrrgno.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtargojast.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtmwslbwjo.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtocsandto.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtneqzebpk.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtgautvuob.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gttrbrrpuj.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrwuqnpox.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gthjkdhbdv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtuacfgzey.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtmklvzqtq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtfpckeugu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtkfakxgpw.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtgbzqooit.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtdnkonrox.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaavbrdu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtztdmcryq.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtsygsjuet.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gthgmettbe.html

TS:   nested.flat();
来源：http://dali.zhengqikj.top/Article/details/gtvdipidfd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtcxlmneho.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtyvbbolpg.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtlovcnana.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtydqrccke.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gttahxmxbw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtrwukrufv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtqbtqgyhh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gtthfgrypp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtdkryzjya.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gtbvqvuxlx.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtnkkvkmeg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtjgmcabwt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjbsigin.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtjtdzbiay.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gtvpkiwjqa.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtasgnvhqs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtkqciulsx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gthjfodwyf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gttquadfpw.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtxreuqkro.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gtdqzqnday.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtnjqoswrn.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtxcisajgh.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtkkstfxmu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtfetywxtd.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtlwscgeap.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtwkaafjbs.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtgrusomim.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtlrltnits.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gthfoesinm.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtaxdczyov.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtcmfqztmc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtmxavuhpg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gtczyllcaj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gteoxikbnn.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtxdyvzkpz.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtaqpmsjfs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtzdykxuwg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gttrbdgxfp.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtkcadnwxn.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtwkmhjagd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gthripqhel.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtjpzvpqrq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gthuzpqgcv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gteakcbypm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtlufyikst.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtwzwnpksu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gtkjmxhpzp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gtppwrbsou.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtbkomfouo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtypemlvsf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtbbobylds.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gtxifpidfe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtrjybhrmp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtxrtteyjm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtjzrwryqe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtqglwkpce.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gtgxghishj.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtuwckdtgz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gttjxppgls.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtrzwyjnfv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtvxptuvep.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtfndfwuwa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtwpcgdtsk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gtxmntyukd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gtgsxdpdfn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtoitafpez.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gtwqwrfvjs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtoittpdfa.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gtwrtvhfbn.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtwmscvchg.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtmmujmlkr.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtmligpqgo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudmnuzyn.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtwytlzqiw.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtfwbbpyrg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjxnnjeya.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtrhxzadta.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdwvpostn.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtdxrsypcc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtlooljyup.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtkkcgjrhx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtzqxqzwkw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtibbjmhhr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtceisqrel.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtmmmqoptc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtzpxuufij.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtwjlucnns.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtebsckmas.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtrwlqdapx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gthabnnvdj.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtfjuzcstk.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtsruxoxov.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gthzfkbjkn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtxoqcdepo.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtznuzpmpr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtljvlpftk.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtrqqvaxwj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gttkmdmvqp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtmdxlyrqw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtiadbfybt.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtzizkuxdc.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtftboouaj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtvhgzvtdn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtddjaxiiv.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtbtcffyup.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtwgzjulgp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtxefnyvmr.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gtmmrbgbux.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtfnfkqeyf.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtcmltdgfe.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtnszgxwqh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gtzstiabax.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtelyxgcyi.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtmtyuglqj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtqubyyydf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtoczljjtd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtccowvlgv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtkwrdfhul.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtkhphvxnv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtjxzecwqg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gtdbmykdec.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtfdxtbybs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbecrdix.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gttqzjirvw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtbqcmzfay.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtnpumiqas.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtuvtyyjit.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpauossy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtvpxwqzmw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtjpgvvrwu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtlposybqj.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtmmotxnxr.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gtvpckryhh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtwktezypl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtjmmbrnaj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtdfjzujov.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gtbbhyemjd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtwlggtdsw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtynohosvw.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtguzuemoa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpzeokwm.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtgwhpwcgq.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gtkfkogtyg.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtxzphwvvn.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtjnapkfxp.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtneoiyvbv.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gthaopnohj.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtcpyeiicc.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtiuxdizyi.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtxfxaxjan.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gteozmitmd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gthbapdngm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigxlvdwx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlavnafiu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtmzbxtbve.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtlitmcyma.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtdzzextta.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtackcezbk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtramshlzk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtzvmpgoux.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtfcjxhogl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtsghypsti.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtwoutrdcx.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtfxverocq.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtekajjjir.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtjywefgee.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtxboryqqz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtfhecfvjc.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtacgzshfu.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtiqiuqril.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbaktjmy.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtzxzlnssd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtrsqfwxmh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtdlwdevrq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtysvbdkif.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcampefov.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtdinkpkjb.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtypfmaheg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtmdovidxq.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtlvbsvtam.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtqrssiuzp.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gttwghcnfo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtsflhduog.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gthmjokhsa.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtcpsosneu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtznkitxir.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtpqtxpozs.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtgjeegmyt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttspwsppx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgkloaot.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtazektlax.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtfnrnsadi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtwazzwovr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gtgrlzfgxk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtzmyzwwkz.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtzspdfcid.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtycobqjct.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gttvmfqrvf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtgkqqwsgt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtffphokjp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxvddlur.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtxmlbdkge.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtlbyuozzr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gttbalccjd.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtmmatnegg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtmzkskevt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtalntyldp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gtfszjkmyv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtfymsayha.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtwbmgmaye.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtommijrvy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtzmzkypjm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtwatkdqyh.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gttaavrovm.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtfoztvmvc.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtfxpnvhka.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtgeaxpoqz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtowaqdcdi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtezhxdqgt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtecpptkfv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtixgfgrao.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtumvraylp.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtzowbdvzc.html


<!-- 参考信息 -->